# 🩻 Medical Imaging Analysis Agent

> Upload any medical scan — X-ray, MRI, CT, or Ultrasound — and get instant AI-powered diagnostic insights. No medical background needed to understand the results.

![Python](https://img.shields.io/badge/Python-3.9+-1D9E75?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-185FA5?style=flat-square&logo=streamlit&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5_Pro-Multimodal_AI-534AB7?style=flat-square&logo=google&logoColor=white)
![Agno](https://img.shields.io/badge/Agno-Agentic_Framework-854F0B?style=flat-square)
![Live](https://img.shields.io/badge/Live-Deployed-1D9E75?style=flat-square)

🔗 **[Open Live App](https://medical-imaging-analysis-agent-zg74hbtofaei7zabb7t3sw.streamlit.app/)**

---

## What is this?

This is an **Agentic AI application** that analyzes medical images using Google's Gemini 2.5 Pro multimodal model. You upload a scan, and the AI agent reasons through it step by step — identifying what type of scan it is, what body part is shown, what looks normal, and what might need attention.

The results are presented in plain English, so anyone can understand them — not just doctors.

---

## How It Works

Step 1 → Upload your image (X-ray, MRI, CT scan, or Ultrasound)
Step 2 → Gemini 2.5 Pro reads and understands the image
Step 3 → The Agno agent applies structured diagnostic reasoning
Step 4 → You receive clear findings + a plain-English explanation

---

## Features

| Feature | Description |
|---|---|
| 🔍 Scan type detection | Automatically identifies X-ray, MRI, CT, or Ultrasound |
| 🫁 Anatomy recognition | Identifies which body part or region is in the scan |
| ⚠️ Abnormality detection | Highlights unusual patterns or areas of concern |
| 📋 Structured report | Findings organized in a clean diagnostic format |
| 💬 Plain-English summary | Translates medical findings into simple language |

---

## Tech Stack

| Tool | Role |
|---|---|
| **Python** | Core language |
| **Streamlit** | User interface |
| **Google Gemini 2.5 Pro** | Multimodal AI model (image understanding) |
| **Agno Framework** | Agentic reasoning layer |

---

## Run It Locally

**Prerequisites:** Python 3.9+ and a Google Gemini API key
```bash
# 1. Clone the repo
git clone https://github.com/your-username/medical-imaging-agent
cd medical-imaging-agent

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your Gemini API key
echo "GOOGLE_API_KEY=your_key_here" > .env

# 4. Launch the app
streamlit run ai_medical_imaging.py
```

Then open your browser at `http://localhost:8501`

---

## Project Structure

medical-imaging-agent/
├── ai_medical_imaging.py   # Main Streamlit app
├── requirements.txt        # Python dependencies
├── .env                    # API keys (not committed)
└── README.md

