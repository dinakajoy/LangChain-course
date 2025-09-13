# LangChain Course

A collection of notebooks documenting my journey learning **LangChain** — covering core concepts, agents, embeddings, vector stores, and building Q&A over private data.

---

## 🚀 What’s in here

| Notebook | Topic |
|----------|-------|
| `1_langchain-deepdive.ipynb` | Foundations of LangChain: chains, prompts, basic usage |
| `2_langchain-agents.ipynb` | Using agents: how to define tools, orchestrate agent behavior |
| `3_pinecone_deepdive.ipynb` | Exploring Pinecone vector store integration, indexing & retrieval |
| `4_langchain-embeddings.ipynb` | Embeddings: creating, comparing, using them for search or similarity |
| `Q&A-on-private-data.ipynb` | Building question-answering workflows over private or custom datasets |

There’s also a `.langchain.db` file and a `chroma_db/` folder (if you used Chroma vector store) for managing data storage/embeddings.

---

## 🚀 Getting started

1. Clone the repo:  
   ```bash
   git clone https://github.com/dinakajoy/LangChain-course.git
   cd LangChain-course
   ```
2. (Optional) Create a virtual environment and install dependencies, e.g.:
   ```
   python -m venv venv
   source venv/bin/activate   # or `venv\Scripts\activate` on Windows
   pip install -r requirements.txt
   ```
3. Open the notebooks in Jupyter (or Google Colab) and run cells to follow along.

---

## 🚀 Usage

- Use the notebooks in order for a progressive learning curve.
- Re-run cells to regenerate vector stores or embeddings if needed.
- Use your own API keys / credentials for services like Pinecone / OpenAI.
- For Q&A over private data, replace the sample/private data with your own dataset and adjust paths.

---

## ⚠️ Notes

- The `.langchain.db` file and vector store folder(s) may become large. Add them to .gitignore if needed.
- Be careful with sensitive credentials (API keys), **do not commit them.**

---

## 🚀 Contact & Contributing

If you find errors or want to suggest improvements, feel free to open an issue or submit a pull request.

Happy learning!
