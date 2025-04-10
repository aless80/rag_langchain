# Agentic RAG

Agentic Retrieval-Augmented Generation [RAG] application.

## Installation and usage

1. Install dependencies using Poetry:

```bash
poetry install
```

2. Place input text files in `local_storage`. Supported formats are `.txt`, `.pdf`, `.md`, `.csv`, `.html`. 

3. Copy the environment file:

```bash
cp .env_mock .env
```

4. Edit `.env` to specify your configuration settings. 


### Command Line Interface
To run the RAG from the command line:

```bash
python main.py cli
```