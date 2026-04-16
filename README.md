# 📄 AI Resume Screening System

An AI-powered web application that evaluates how well a candidate’s resume matches a given job description.

## 🚀 Features
- Extracts key skills from resume text
- Matches resume skills with job requirements
- Calculates a matching score (0–100)
- Generates a short explanation for the score
- Simple and interactive UI using Streamlit

## 🛠️ Tech Stack
- Python
- Streamlit (UI)
- Transformers (Hugging Face)
- Basic NLP (skill matching logic)

## 📊 How It Works
1. User pastes resume and job description
2. System extracts relevant skills
3. Compares with predefined job skills
4. Calculates a matching score
5. Generates explanation using a language model

## ▶️ How to Run

```bash
pip install streamlit transformers
python -m streamlit run app.py

📸 Demo
<img width="1066" height="777" alt="UI 1" src="https://github.com/user-attachments/assets/6458997d-b0b8-4023-9e33-d16a8327f405" />

<img width="887" height="423" alt="UI 2" src="https://github.com/user-attachments/assets/65093084-d9f2-402c-bf5f-94524b235143" />


⚠️ Note
This project uses a lightweight local model (distilgpt2) for text generation.
Explanation quality may be basic.
Can be improved using advanced instruction-tuned models.
🔮 Future Improvements
Upload resume as PDF
Better AI model for explanation
Automatic skill extraction using NLP
Improved UI/UX
👩‍💻 Author
Mayuri Rathod.
