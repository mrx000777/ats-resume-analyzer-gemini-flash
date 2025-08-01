# 📝 Resume ATS Scanner App using Gemini 1.5 Flash

This project is an **AI-powered Resume ATS (Applicant Tracking System) Checker** that uses **Google's Gemini 1.5 Flash model** to analyze resumes against job descriptions and provide intelligent feedback on ATS-friendliness and matching score.

---

## 🔧 Tech Stack

- 🧠 **Gemini 1.5 Flash** via Google Generative AI API  
- 🐍 **Python**
- 📄 **PDF processing** with `PyMuPDF`
- 🌐 **Streamlit** for Web UI
- 📦 **Google Generative AI SDK**
- 🛠️ **LangChain** (optional: for prompt chaining or future enhancements)

---

## 🚀 Features

- ✅ Upload **Resume (PDF)**
- ✅ Input **Job Description (text)**
- 🤖 Gemini 1.5 Flash compares and evaluates:
  - Resume vs Job description
  - Relevance score
  - Skills & keywords match
  - ATS-friendliness feedback
- 📊 Simple & Interactive Streamlit interface
- 🔐 API key support for secure model access

---

## 📸 Screenshots

| Upload Resume | Result Summary |
|---------------|----------------|
| <img width="1021" height="709" alt="Screenshot 2025-08-01 113131" src="https://github.com/user-attachments/assets/3c72d842-7b67-40b3-82a1-b5b59143d028" />
 |<img width="1071" height="685" alt="Screenshot 2025-08-01 113148" src="https://github.com/user-attachments/assets/66059db7-e7df-4505-9109-9bb29449b0f9" />
|

---

## 🗂️ Project Structure

```
📁 ats_resume_scanner/
├── app.py                     # Streamlit application
├── utils.py                   # PDF and image conversion
├── requirements.txt           # Required libraries
├── README.md                  # Project documentation
└── .env                       # For storing Gemini API key
```

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/ats_resume_scanner.git
cd ats_resume_scanner
pip install -r requirements.txt
```

---

## 🔐 Setup API Key

1. Get your API key from: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Set your API key:

**Option 1 (recommended):**  
Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

**Option 2 (in-code):**

```python
import google.generativeai as genai
genai.configure(api_key="your_api_key_here")
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 💡 Future Enhancements

- Job matching score visualization
- Auto-suggestions to improve resume
- Support DOCX format
- Multi-resume bulk analysis
- Chat interface using LangChain agents

---

## 👤 Author

**Manish Thakur**  
GitHub: [@mrx000777](https://github.com/mrx000777)  
Feel free to connect and contribute!

---

## 📄 License

MIT License – feel free to use and contribute.
