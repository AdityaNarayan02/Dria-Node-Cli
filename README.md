# Dria-Node-Run-Full-Guide

## Requirements

### Software

Depending the AI models of your choice, you may have to install software:

- **OpenAI models**: you don't have to install anything, we just need an `OPENAI_API_KEY`!
- **Ollama models**: For VPS and WSL(in windows)

  ```sh
  curl -fsSL https://ollama.com/install.sh | sh
  ```
- **Ollama models**: you have to install Ollama, see [download instructions here](https://ollama.com/download). After installing, confirm you have it with:

  ```sh
  ollama --version
  ```

  
### Hardware

**To learn about hardware specifications such as required CPU and RAM, please refer to [node specifications](SystemRequirements.md).**

In general, if you are using Ollama you will need the memory to run large models locally, which depend on the model's size that you are willing to. If you are in a memory-constrained environment, you can opt to use OpenAI models instead.
