
![Screenshot 2025-07-08 203522](https://github.com/user-attachments/assets/f59e772a-bbd1-4f45-8283-a083b30c4a6b)


# 🧠 DataFrame ChatBot – Ollama + LangChain

This is a **Streamlit web application** that lets you **chat with your CSV or Excel datasets using natural language**. It leverages **LangChain**, **Ollama**, and the **Gemma 3** LLM to analyze your data and respond conversationally.

---

## 🚀 Features

- 📁 Upload `.csv`, `.xlsx`, or `.xls` files
- 💬 Ask questions about your data in plain English
- 🤖 Uses a local LLM via Ollama (`gemma3:latest`)
- 🧠 Maintains chat history for multi-turn conversations
- 🛡️ Fully local – no data leaves your machine

---

## 🛠️ Tech Stack

- `pandas` – for data processing
- `langchain` – LLM orchestration framework
- `langchain-experimental` – tools for DataFrame interaction
- `langchain-ollama` – integrate with Ollama local models
- `streamlit` – interactive web UI
- `ollama` – runs the Gemma model locally

---

## 📦 Installation

1. **Install Python dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

2. **Install [Ollama](https://ollama.com/)** and run the Gemma model:

   ```bash
   ollama run gemma3
   ```

---

## ▶️ Usage

Run the app using Streamlit:

```bash
streamlit run main.py
```

1. Upload a CSV or Excel file
2. Ask questions like:
   - `"What is the average salary?"`
   - `"Show top 5 rows by sales"`
   - `"Which category had the highest revenue?"`
3. View real-time LLM-powered responses

---

## 📁 File Structure

```
.
├── main.py             # Main Streamlit application logic
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🧪 Example Questions

- `"What is the total revenue in the dataset?"`
- `"Find rows where age > 30"`
- `"Summarize the sales trend"`

---


## 📝 License

MIT License

---

## 🙌 Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain)
- [Ollama](https://ollama.com/)
- [Streamlit](https://streamlit.io/)
