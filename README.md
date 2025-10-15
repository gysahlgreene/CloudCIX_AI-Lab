# CloudCIX AI Lab for Open OnDemand

An interactive AI laboratory application for Open OnDemand that integrates oobabooga's text-generation-webui.

## Attribution

This project integrates [text-generation-webui](https://github.com/oobabooga/text-generation-webui) 
by oobabooga to provide text generation capabilities in an Open OnDemand environment.

- Original project: https://github.com/oobabooga/text-generation-webui

## Features

- Run large language models directly in your browser
- Access to multiple model architectures (LLAMA, Mistral, etc.)
- Text generation with customizable parameters
- Chat interface with character customization
- Instruction-following templates
- Training and fine-tuning capabilities
- LoRA adapters support

## Prerequisites

- Open OnDemand environment
- Apptainer/Singularity


## Directory Structure

The application creates the following directory structure in the user's home:

```
~/cloudcix_ai_lab/
├── models/
├── loras/
├── characters/
├── presets/
├── logs/
├── cache/
└── settings/
```

