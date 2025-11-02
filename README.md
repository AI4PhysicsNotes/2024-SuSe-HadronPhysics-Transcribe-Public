# 2024 RUB Hadron Physics

It's an experimental project of utilising LLM to shape the lecture script from audio transcription and students handwiritten notes.

The content is based on the Course materials for Hadron Physics lectures tought in Ruhr University Bochum.

[![Pages](https://img.shields.io/badge/Pages-RUB%20Hadron%20Physics-blue)](https://ai4physicsnotes.github.io/2024-SuSe-HadronPhysics-Transcribe-Public/)

## Automation

The lecture index is automatically generated based on the actual Markdown files present in the repository. Missing lectures are shown as gray, unclickable buttons.

### Local Development

To regenerate the index locally:
```bash
python3 generate_index.py
```

The index will be generated as `Lectures/index.html` with buttons for all available lectures and gray placeholders for missing ones.

### LLMs used in this project

External:
 - Deepseek for main processing
 - OpenAI gpt-4-mini for image reconition

Local (in Ollama interface):
 - [`mirth/chonky_modernbert_large_1`](https://github.com/mirth/chonky)
 - `snowflake-arctic-embed2` for creating larger simularity blocks
 - `all-minilm:33m` and `qwen3-embedding:8b` for image insertion 


