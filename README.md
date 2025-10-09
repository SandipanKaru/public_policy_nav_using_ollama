# 📘 **Project Documentation**

---

## 📌 **Project Title**
### **Text Chunking and Summarization with Streamlit & Ollama**

---

## 📖 **Overview**

This project demonstrates how to:

- 📤 **Upload documents** using **Streamlit**
- ✂️ **Process text into chunks** with overlap to avoid broken or meaningless sentences
- 🤖 **Integrate with Ollama** for AI-based summarization and analysis
- 💾 **Store the project on GitHub** with version control
- ⚖️ **License the project** under the MIT License

---

## 🚀 **Features**

- 📂 **File upload interface** (Streamlit)
- ✂️ **Intelligent text chunking** with overlap (fixes issues like *ministry → nistry*)
- 🤖 **AI summarization** using Ollama
- 💾 **GitHub repository** for code management
- 📜 **MIT License** for open-source use

---

## 🛠️ **Tech Stack**

- 🐍 **Python 3.x**
- 🎛️ **Streamlit** (UI & file upload)
- 🧠 **Ollama** (LLM integration)
- 🗃️ **Git & GitHub** (version control)

---

## ⚙️ **Installation**

### 1️⃣ Create & activate a virtual environment:

```bash
python -m venv venv
# Windows
venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run app.py

```

🧩 **Code Workflow**

• Streamlit Upload – User uploads document.

• Chunking Function – Splits text into overlapping chunks.

• Ollama Integration – Each chunk is sent for summarization.

• Output Display – Summarized results shown in Streamlit.

📑 **Example Output**

*Input Document*: Public Policy of Germany
Generated Chunks:

*Chunk 1*: Overview of education system...

*Chunk 2*: DigitalPakt 2019 with €5 billion...

*Chunk 3*: Ministry programs on digital literacy...

**Summarization Result (via Ollama)**:
A concise overview of Germany’s public education policies focusing on digital transformation and vocational training.

📜 **License**

This project is licensed under the MIT License

👨‍💻 **Author**

*Sandipan Karu*