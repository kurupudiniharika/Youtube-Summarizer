# Gemini-Powered YouTube Summarizer

## 📖 About This Project
This is a **Gemini-powered web application** that takes a YouTube link as input and provides a concise AI-generated summary. It uses **Google's Gemini API** via the **Google Gen AI SDK** and is built with **Flask** for the backend and deployed on **Cloud Run**.

---
## 🚀 Features
- Summarizes YouTube videos using **Gemini 2.0 Flash**.
- Allows additional prompt customization.
- Simple and clean UI with HTML + CSS.
- Backend powered by **Flask**, deployed to **Cloud Run**.
- Uses **Google Gen AI SDK** for Gemini API calls.

---
## 📋 Prerequisites
- A **Google Cloud Project** with billing enabled.
- Enabled APIs:
  - Vertex AI API
  - Cloud Run Admin API
  - Cloud Build API
  - Cloud Resource Manager API
- Python 3.10+
- Basic knowledge of **Flask**, **HTML**, and **Google Gen AI SDK**.

---

## 📦 Project Structure
## ⚙️ Tech Stack
- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS
- **AI Model:** Gemini 2.0 Flash
- **Hosting:** Google Cloud Run
- **SDK:** google-genai

---

## 📜 Installation
   Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gemini-youtube-summarizer.git
   cd gemini-youtube-summarizer
# Create a virtual environment & install dependencies:
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

Set your Google API Key:
export GOOGLE_API_KEY="your_api_key_here"

# Run locally:

python app.py

## 🚀 Deployment

# Deploy to Cloud Run:

gcloud config set project [PROJECT_ID]
gcloud run deploy --source .


