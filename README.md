
# 🧠 RAG PDF Assistant

Conversational Retrieval-Augmented Generation (RAG) application for interacting with uploaded PDF files. Powered by LangChain, Groq LLMs, and Streamlit — this app allows you to ask questions about your PDFs and get intelligent answers with context-aware chat history.

---

## 🚀 Features

- 📄 Upload and interact with multiple PDFs
- 🧠 Uses RAG (Retrieval-Augmented Generation) for accurate answers
- 💬 Maintains chat history across sessions
- 🔍 Reformulates questions using previous conversation context
- ⚡ Powered by [Groq](https://groq.com/) (Gemma2-9b-It) and HuggingFace embeddings
- 🌐 Clean, interactive Streamlit interface

---

## 🛠️ Tech Stack

- **Frontend/UI**: Streamlit
- **LLM**: Groq API (`Gemma2-9b-It`)
- **Embeddings**: HuggingFace (`all-MiniLM-L6-v2`)
- **Vector Store**: ChromaDB
- **Document Processing**: LangChain, PyPDFLoader

---

## 📦 Installation

```bash
git clone https://github.com/RandomRohit-hub/rag-pdf-assistant.git
cd rag-pdf-assistant
pip install -r requirements.txt
````

---

## 🔐 Environment Variables

Create a `.env` file in the project root and add your HuggingFace token:

```env
HF_TOKEN=your_huggingface_token
```

You will be prompted to enter your **Groq API Key** within the app interface.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 🖼️ Usage

1. Start the app and enter your **Groq API Key**.
2. Upload one or more PDF files.
3. Enter a **Session ID** to track conversation history.
4. Ask questions based on the content of the uploaded PDFs.
5. Get context-aware responses with persistent chat history.

---

## 🧪 Example Use Cases

* Summarizing long academic papers
* Extracting key facts from reports
* Legal document Q\&A
* Conversational interface for PDF-based knowledge bases

---

## 📌 Notes

* All PDFs are processed locally before embedding and querying.
* Chat history is session-based and persistent as long as the app runs.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* [LangChain](https://www.langchain.com/)
* [Streamlit](https://streamlit.io/)
* [Groq](https://groq.com/)
* [Hugging Face](https://huggingface.co/)
* [Chroma](https://www.trychroma.com/)

---

## 🤝 Contributing

Pull requests and issues are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

