# AI Chemist — Tablet Identification with Gemini Vision

An AI-powered app that identifies medication tablets from a photo and explains their uses, dosage context, and key characteristics — built using Google's Gemini 1.5 Flash vision model.

Built during a Generative AI Internship — Google Cloud Generative AI (SmartInternz).

## Features
- Upload a photo of a tablet/medicine package
- Gemini Vision analyzes the image and identifies the medication
- Returns a structured breakdown: uses, functionality, dosage context, and distinguishing features

## Tech stack
- Streamlit — web app UI
- Google Generative AI (Gemini 1.5 Flash) — image understanding
- Python-dotenv — environment variable management
- Pillow — image handling

## How to run
```bash
pip install -r requirements.txt
```
Create a `.env` file in the project root with:


GOOGLE_API_KEY=your_api_key_here

Then run:
```bash
streamlit run app.py
```

## Example
Upload a photo of a tablet box → get an AI-generated summary of what it is and what it's used for.

