# 📚 STUDY (PYQhub) — AI-Powered Smart Learning Platform

STUDY (PYQhub) is an AI-powered smart study platform for school (CBSE/ICSE) and university students. Features automated PDF exam paper extraction with diagram cropping (PyMuPDF), AI-classified chapter-wise question banks, on-demand step-by-step solutions, dynamic mock test generators, and an AI study mentor powered by Google Gemini.

---

## ✨ Key Features
- **Dual Student Domains**: Dedicated learning tracks for School (CBSE/ICSE Class 10) and University students.
- **Automated PDF Parsing & Diagram Cropping**: Ingests exam paper PDFs, automatically classifies questions by chapter using Gemini AI, and clips question diagrams/figures with PyMuPDF.
- **Chapter-Wise PYQ Bank**: Filter and search questions by Board, Class, Subject, and Chapter.
- **AI Smart Explainer**: Instant step-by-step solutions, formulas, and explanations for any question.
- **Dynamic Mock Test Generator**: Produces custom MCQs and high-yield questions based on historical exam trends.
- **"The Night Before" Exam Sprint**: Emergency last-minute cramming roadmap with formula cheat sheets and top repeated questions.
- **AI Study Mentor & Counselor**: Built-in empathetic chatbot for academic guidance and exam stress relief.

## 🛠️ Tech Stack
- **Backend**: Python 3, Django 6
- **AI / LLM**: Google Gemini API (`google-genai`)
- **PDF & Image Processing**: PyMuPDF (`fitz`), Pillow
- **Frontend**: HTML5, Vanilla CSS, Tailwind CSS, Material Symbols
- **Database**: SQLite

## 🚀 Getting Started

### 1. Prerequisites
- Python 3.10+
- (Optional) Gemini API Key for AI features

### 2. Setup & Installation
```bash
# Clone the repository
git clone https://github.com/Deepaliluthra185/STUDY.git
cd STUDY

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# (Optional) Create .env for Gemini API key
# GEMINI_API_KEY="your_api_key_here"

# Start development server
python manage.py runserver
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.
