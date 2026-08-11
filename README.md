# LLM & RAG Workshop (SUT)

Technical workshop materials covering **transformer architecture** (attention
mechanisms, multi-head attention, next-token prediction) and hands-on
**LangChain RAG pipeline** development — vector indexing, Top-K vs. MMR
retrieval optimization, prompt engineering, and chatbot deployment via Gradio.

Delivered for astronomy researchers and students at Suranaree University of
Technology (SUT).

## Contents

| File | Description |
|------|-------------|
| `LLM-Workshop-Day1.pdf` | Day 1 slides — transformer architecture & LLM fundamentals |
| `RAG-Workshop-Day2.pdf` | Day 2 slides — Retrieval-Augmented Generation |
| `HandOn1_LangChain Basics.ipynb` | Prompt templates, chat prompts, message history |
| `HandOn2_Document Processing & Embeddings.ipynb` | Text splitters, chunking, embeddings |
| `HandOn3_Vector DB & Retriever.ipynb` | FAISS vector store, Top-K vs. MMR retrievers, Gradio |
| `HandOn4_RAG.ipynb` | End-to-end RAG chain + bring-your-own-document practice |
| `API-key-setup-guide.pdf` | Walk-through for creating your own Hugging Face and Groq API keys |

## Getting started

The notebooks are designed to run in **Google Colab**. API keys are read from
Colab secrets (`userdata.get(...)`) or environment variables — **no keys are
stored in this repository**. Set your own key before running.

## License

This repository uses **two licenses** for its two kinds of content:

- **Code** (the `*.ipynb` notebooks) is licensed under the **MIT License** —
  see [`LICENSE-CODE`](LICENSE-CODE).
- **Teaching materials** (the `*.pdf` slide decks) are licensed under
  **CC BY-NC-SA 4.0** — see [`LICENSE-CONTENT`](LICENSE-CONTENT).

In short: you may reuse and adapt these materials **with credit** and
**not for commercial purposes**. For commercial use, please contact the author.

## Attribution

Created by **Parinya Duangklang** (<https://github.com/parinyad123>).
If you use or adapt these materials, please credit the author and link back to
this repository.
