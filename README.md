# Resume Selection System 🧠📄

This project is a **resume filtering and selection system** designed to assist recruiters in efficiently shortlisting candidates based on job requirements using Natural Language Processing (NLP).

## 🚀 Features

- ✅ Upload and parse resumes (PDF format)
- 🔍 Extract relevant information (skills, education, experience)
- 🧠 Match resumes with job descriptions using NLP similarity
- 📊 Rank candidates based on match percentage
- 🖼️ Web interface using Streamlit

## 🛠️ Tech Stack

- Python
- Streamlit
- spaCy (NLP)
- PyPDF2 / pdfminer (for PDF parsing)
- Scikit-learn (TF-IDF Vectorizer & Cosine Similarity)

## 📁 Project Structure

Resume_Selection/
├── app.py # Main Streamlit application
├── parser.py # Resume parsing and preprocessing logic
├── ranker.py # Similarity matching and ranking
├── requirements.txt # Dependencies
└── resumes/ # Folder to store uploaded resumes

## 🧪 How It Works

1. Upload multiple resumes through the Streamlit interface.
2. Enter or paste a job description.
3. The system parses resumes using NLP, computes TF-IDF vectors, and ranks them based on cosine similarity.
4. Displays a ranked list of candidates with matching scores.

## ✅ How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/ar-baazaja/Resume_Selection.git
   cd Resume_Selection

   pip install -r requirements.txt

   streamlit run app.py
