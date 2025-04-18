# 🖼️ Image Caption Generator using Google Gemini

A simple Streamlit app that uses **Google Gemini 1.5 Flash** to generate AI-powered captions for uploaded images.

## 🚀 Features
- Upload `.jpg`, `.jpeg`, or `.png` images
- Generates smart, descriptive captions using Gemini API
- Clean and interactive Streamlit UI

## 🛠️ Requirements
- Python 3.7+
- Google Gemini API key
- Dependencies: `streamlit`, `Pillow`, `google-generativeai`

## 📦 Installation & Usage

```bash
# 1. Install dependencies
pip install streamlit Pillow google-generativeai

# 2. Add your Google Gemini API key inside app.py
# Replace:
genai.configure(api_key="your-api-key-here")

# 3. Run the app
streamlit run app.py
