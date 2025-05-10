# LittleRAGChatbot

This is an interactive chatbot built in Google Colab using LangChain, OpenAI GPT-4o, and a small RAG (Retrieval-Augmented Generation) pipeline.

### Features

- Uploads and indexes a custom set of papers (PDFs) using FAISS
- Retrieves relevant chunks based on user questions
- Combines retrieved context with ChatGPT via LangChain
- Falls back to general GPT knowledge if no paper content is found
- Maintains chat memory and logs responses

### How to Use

1. Run all cells in the notebook.
2. Enter your OpenAI API key when prompted.
3. Ask anything! If the topic is in your uploaded papers, it uses them; otherwise, it falls back to general knowledge.

> Example prompt: `Tell me about the doppelgänger effects in my VR study.`

---

**Author**: [Siqi Guo](https://github.com/SiqiGuo477)
# LittleRAGChatbot
