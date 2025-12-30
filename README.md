# "The Essential Guide to AI Companions: From Technical Foundations to Social Impact" - Chapter 3, Code

This repository contains practical code examples from Chapter 3 of Giada Pistilli's "The Essential Guide to AI Companions: From Technical Foundations to Social Impact" book, demonstrating how to build responsible AI companion systems using open-source models.

## Overview

The code implements a modular AI companion architecture with three core pillars:
- **Memory System**: Manages conversation history and context retention
- **Personality Engine**: Defines AI behavior and ethical boundaries through system prompts
- **Emotional Recognition System**: Detects emotional content using vector similarity

## Prerequisites

- Python 3.9 or higher
- A Hugging Face account and API token (free)
- Approximately 4-6 GB of free disk space for model weights
- 8 GB RAM minimum (16 GB recommended)

## Installation

1. **Clone or download this repository**

2. **Install required packages:**

```bash
pip3 install transformers torch
```

3. **Get your Hugging Face token:**
   - Create a free account at [huggingface.co](https://huggingface.co)
   - Go to Settings → Access Tokens
   - Create a new token (read access is sufficient)
   - Accept the Gemma model license at [google/gemma-3-1b-it](https://huggingface.co/google/gemma-3-1b-it)

4. **Add your token to the code:**

Replace `HF_TOKEN = "xxxxxxxxxxx"` with your actual token in the notebook cells.

## Running the Code

### Option 1: Jupyter Notebook

```bash
jupyter notebook chapter_code.ipynb
```

Run cells sequentially from top to bottom.

### Option 2: Python Script

Extract any code cell and run it as a standalone Python script. Each major section can run independently after the initial setup.
