[![Midori AI photo](https://tea-cup.midori-ai.xyz/download/logo_color1.png)](https://io.midori-ai.xyz/)

### Built with
- ``UV``

## Quick-start
```bash
# Use this python file to chat with a LRM
uv run lrm_chat.py

# use this python file to output data to finetune your own LRM using tools like `unsloth`
uv run lrm_qna_trainer.py
```

## How it Works

Both `lrm_chat.py` and `lrm_qna_trainer.py` contribute to a Large Reasoning Model (LRM) workflow.

*   `lrm_chat.py`: This script serves as an interactive testing environment for LRMs.  Users can experiment with different models and prompts to evaluate their performance in a conversational setting. Think of it as a sandbox for LRM exploration and validation.

*   `lrm_qna_trainer.py`: This script focuses on knowledge extraction and preparation. It processes a text file and transforms the data into a structured JSON format. This JSON output is designed for use in other applications (IE ``unsloth``), effectively creating a knowledge base for LRMs to draw upon.  In essence, it's a data pipeline for training or augmenting LRMs with specific information.

## Pre-requisites

Install ``UV`` from your package manager or from [here](https://docs.astral.sh/uv/getting-started/installation/)

- **System requirements**:
  - OS: Windows, macOS, or Linux
  - Python: None, Use ``UV``
  - Minimum RAM: 10GBs
  - Disk space: 5GBs to 15GBs

- **Dependencies**:
  - ``UV`` auto installs all dependencies into a venv for you

## Contributing

Contributions are welcome!