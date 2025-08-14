# 🧠 Sentiment Analyzer – Mistral via Ollama

The **Sentiment Analyzer** is a lightweight AI-powered application that classifies text sentiment as **Positive**, **Negative**, or **Neutral** using the **Mistral model** via [Ollama](https://ollama.com).

This project is built with:

- **FastAPI** – Backend API to process requests
- **Streamlit** – Interactive frontend UI
- **Ollama (Mistral)** – Local AI model for sentiment analysis
- **GitHub** – Version control and publishing

---

## 🚀 Features

- **FastAPI backend** – Simple, fast, and scalable
- **Streamlit frontend** – Clean, interactive web interface
- **Local AI processing** – Sentiment analysis runs entirely on your machine
- **Lightweight Mistral model** – Fast response and accurate classification
- **Privacy-first** – No data sent to external servers

---

## 🛠 Tech Stack

- **Backend:** FastAPI, Uvicorn, Requests
- **Frontend:** Streamlit
- **Model:** Mistral via Ollama
- **Language:** Python 3.10+

---

## 📂 Project Structure

```
sentiment-analyzer-mistral/
│── backend/
│   └── main.py          # FastAPI backend
│── frontend/
│   └── app.py           # Streamlit frontend
│── requirements.txt     # Python dependencies
│── README.md
│── venv/                # Virtual environment
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install Ollama

Download and install Ollama:  
[https://ollama.com/download](https://ollama.com/download)

Pull the **Mistral** model:

```bash
ollama pull mistral
```

### 2️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/sentiment-analyzer-mistral.git
cd sentiment-analyzer-mistral
```

### 3️⃣ Create & activate virtual environment

```bash
python -m venv venv

# Windows (PowerShell)
.\venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
```

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App

**Step 1 – Start backend (FastAPI)**

```bash
uvicorn backend.main:app --reload
```

Backend runs at: `http://localhost:8000`

**Step 2 – Start frontend (Streamlit)**

```bash
streamlit run frontend/app.py
```

Frontend opens in your browser at: `http://localhost:8501`

---

## 🧪 Example Usage

1. Enter a sentence in the text area.
2. Click **Analyze**.
3. The app will return **Positive**, **Negative**, or **Neutral**.

---

## 🔮 Future Improvements

- Handle multiple sentences and batch processing
- Show confidence scores
- Add multilingual sentiment analysis
- Integrate with a database for storing analysis history

---

## 🔗 Connect with Me

📧 kanishka96se@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/kanishka96/) | [GitHub](https://github.com/Kanishka96ac)
