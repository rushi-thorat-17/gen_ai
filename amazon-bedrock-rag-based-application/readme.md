# 📚 Enterprise RAG System

An **Enterprise Retrieval-Augmented Generation (RAG) System** built using **Python, Streamlit, AWS Bedrock, Amazon S3, and Boto3**.  
This application enables users to upload enterprise documents, securely store them in Amazon S3, and interact with an AI-powered knowledge base using natural language queries with citation-supported responses.

---

## 🚀 Features

- 🔍 Intelligent document-based question answering
- 📄 Support for TXT, PDF, and DOCX uploads
- ☁️ Secure document storage with Amazon S3
- 🤖 AI-powered responses using AWS Bedrock Foundation Models
- 📚 Retrieval-Augmented Generation (RAG) architecture
- 🖥️ Interactive and responsive Streamlit interface
- 📌 Citation-aware answers from source documents
- ⚡ Fast semantic search and retrieval pipeline

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **Cloud Platform:** AWS  
- **AI Services:** Amazon Bedrock  
- **Storage:** Amazon S3  
- **AWS SDK:** Boto3  
- **Environment Variables:** python-dotenv  

---

## 📂 Project Structure

```bash
enterprise-rag-system/
│
├── app.py                   # Main Streamlit application
├── bedrock_rag.py           # Bedrock integration & retrieval logic
├── config.py                # Configuration and constants
├── requirements.txt         # Python dependencies
├── documents/               # Enterprise sample documents
├── scripts/                 # Deployment and automation scripts
└── README.md
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/enterprise-rag-system.git
cd enterprise-rag-system
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv myenv
```

#### Activate Environment

**Windows**
```bash
myenv\Scripts\activate
```

**Linux / macOS**
```bash
source myenv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔐 AWS Configuration

Create a `.env` file in the project root:

```env
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_DEFAULT_REGION=us-east-1
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📌 System Workflow

1. User uploads enterprise documents
2. Files are stored securely in Amazon S3
3. Bedrock Knowledge Base processes and indexes documents
4. User asks questions through chat interface
5. Relevant document chunks are retrieved
6. AI generates contextual responses with citations

---

## 💡 Example Queries

- What is the company's leave policy?
- Explain the employee onboarding process.
- What are the IT security guidelines?
- Describe the data privacy policy.
- What are the official office timings?

---

## 🌟 Future Improvements

- 🔐 Multi-user authentication system
- 💾 Chat history and session storage
- 📄 AI-powered PDF summarization
- 👥 Role-based document access
- 📊 Admin analytics dashboard
- 🌐 Multi-language support

---

## 📸 User Interface

Simple and modern Streamlit-based interface designed for enterprise document interaction and AI-powered search.

---

## 👨‍💻 Developer

**Mahesh Bodhankar**  
AI / ML / Data Science Enthusiast

---

## 🙌 Acknowledgements

- AWS Bedrock
- Amazon S3
- Streamlit
- Boto3 SDK
- Python Open-Source Community

---

## 📜 License

This project is intended for educational, research, and portfolio demonstration purposes.

---

> 🚀 Developed to demonstrate enterprise-level RAG architecture, cloud-based AI integration, and intelligent document retrieval systems using AWS services.
