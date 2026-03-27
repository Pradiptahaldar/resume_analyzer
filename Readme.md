# 📄 AI Resume Analyzer

An AI-powered web app that analyzes resumes and provides an estimated **ATS (Applicant Tracking System) score**, along with actionable feedback to improve your chances of getting shortlisted.

---

## 🚀 Features

* 📂 Upload resume (PDF format)
* 🔍 Extract and analyze resume content
* 📊 Generate ATS score (out of 100)
* ❌ Identify mistakes and missing sections
* 💡 Provide smart suggestions for improvement
* 🧠 AI-based feedback on content quality

---

## 🧠 How It Works

1. User uploads a resume (PDF)
2. The app extracts text from the file
3. The system analyzes:

   * Keywords relevance
   * Resume structure
   * Content quality
4. Generates:

   * ATS Score
   * Feedback & suggestions

---

## ⚙️ Tech Stack

* **Python**
* **Streamlit** (for UI)
* **PyPDF2 / pdfplumber** (PDF parsing)
* **OpenAI API / LLM** (for intelligent feedback)
* *(Optional)* spaCy for NLP

---

## 🧱 Project Structure

```
resume-analyzer/
│
├── app.py                # Streamlit UI
├── main.py              # Core backend logic
│
├── analyzer/
│   ├── parser.py        # PDF text extraction
│   ├── scorer.py        # ATS scoring logic
│   ├── feedback.py      # AI feedback system
│
├── data/
│   └── keywords.txt     # Job-related keywords
│
├── requirements.txt
└── README.md
```

---

## 📊 ATS Scoring Criteria

The ATS score is calculated based on:

* 🧩 **Keyword Matching** (40%)
* 🏗️ **Resume Structure** (20%)
* ✍️ **Content Quality** (40%)

> ⚠️ Note: This is an **estimated score**, not an exact ATS result. Real ATS systems may vary.

---

## 🧪 How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the app

```
streamlit run app.py
```

---

## 📌 Future Improvements

* 📄 Job description matching
* 🎯 Keyword gap analysis
* ✨ Resume rewriting suggestions
* 📥 Download improved resume
* 🌐 Deploy as a web app

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 💡 Author

Built by **Pradipta Haldar**
trying to do future improvements

