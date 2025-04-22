# Multi-PDF Chat Agent

An intelligent chatbot built with **Streamlit** that allows users to upload multiple PDF documents and ask natural language questions based on their content. It utilizes **LangChain**, **Google's Gemini API**, and **FAISS** for vector storage and semantic search.

---

## Features

- Upload and process multiple PDF documents.
- Ask any question related to the uploaded documents.
- Uses Gemini (`gemini-1.5-flash`) for conversational responses.
- FAISS-powered semantic search for fast and relevant results.
- Clean and user-friendly interface with Streamlit.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/multi-pdf-chatbot.git
cd multi-pdf-chatbot
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables
```bash
GOOGLE_API_KEY=your_google_api_key_here
```
### 5. Run the App
```bash
streamlit run main.py
```
