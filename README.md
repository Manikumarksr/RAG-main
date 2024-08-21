# Retrieval Augmented Generation(RAG)

This repository contains the Retrieval Augmented Generation (RAG) implementation with custom data from PDF. The vector database uses the Qdrant database
which can run in-memory.


**Install the dependencies**

Create the virtual environment and install the dependencies:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
Here is a summary of what this repository will use:
1) Qdrant for the vector database
2) Llamafile for the LLM
3) OpenAI's Python API to connect to the LLM after retrieving the vectors response from Qdrant
4) Sentence Transformers to create the embeddings