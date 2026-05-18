# 💊 MedIntel GPT — AI Assistant for Healthcare & Pharma Insights

MedIntel GPT is an **advanced Generative AI-powered healthcare assistant** built to simplify pharmaceutical and medical information access. It delivers smart, contextual, and human-like responses using powerful Large Language Models with memory-driven conversations.

---

## 🚀 Key Features

- 🤖 AI-powered healthcare chatbot using Gemini LLM
- 🧠 Context-aware memory for intelligent conversations
- 💊 Specialized in pharma and healthcare-related queries
- ⚡ Real-time interactive interface with Streamlit
- 🔄 Persistent session-based chat experience
- 🗑️ One-click chat reset functionality
- 🧩 Clean modular architecture for scalability
- 📚 Smart prompt engineering support

---

## 🛠️ Technology Stack

- **Frontend:** Streamlit
- **LLM Engine:** Google Gemini API
- **Backend:** Python
- **Memory Management:** Session State
- **Architecture Style:** Modular AI System

---

## 📂 Folder Structure

```bash
medintel-gpt/
│
├── main.py                    # Entry point of application
├── core/
│   ├── llm_engine.py          # Gemini API integration
│   ├── chat_memory.py         # Conversation memory logic
│   ├── prompt_engine.py       # Prompt construction module
│
├── .env                       # Environment variables
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/medintel-gpt.git
cd medintel-gpt
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv env
env\Scripts\activate
```

---

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Configure API Key

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key
```

---

### 5️⃣ Launch the Application

```bash
streamlit run main.py
```

---

## 🧠 System Workflow

1. User submits healthcare/pharma query
2. Query gets stored in conversational memory
3. Prompt engine formats contextual input
4. Gemini API generates intelligent response
5. Output is stored and displayed dynamically
6. Continuous conversation context is maintained

---

## 💡 Potential Use Cases

- Drug composition and usage information
- Pharma manufacturing guidance
- Clinical trial knowledge assistance
- Healthcare policy insights
- Medical industry trend analysis
- Research-based AI assistance

---

## 🔒 Environment Variables

| Variable Name  | Purpose                    |
| -------------- | -------------------------- |
| GEMINI_API_KEY | Google Gemini API access   |

---

## 🌟 Future Enhancements

- 🌐 Multilingual healthcare support
- ☁️ Cloud deployment integration
- 📈 AI analytics dashboard
- 🔐 Secure authentication system
- 📤 Exportable chat reports
- 🧾 PDF-based medical document analysis

---

## 📸 User Interface

Minimal and responsive AI chat interface built using Streamlit for seamless interaction.

---

## 👨‍💻 Developer

**Your Name Here**  
AI & Data Science Enthusiast

---

## 🙌 Credits

- Google Gemini API
- Streamlit Framework
- Python Open-Source Community

---

## 📜 License

This project is intended for learning, portfolio building, and research demonstration purposes.

---

> 🚀 Designed to showcase practical implementation of Generative AI, conversational memory systems, and modular healthcare-focused AI applications.
