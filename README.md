# AI Chemist — Tablet Identification with Gemini Vision

An AI-powered app that identifies medication tablets from a photo and explains their uses, dosage context, and key characteristics — built using Google's Gemini API (vision-capable flash model).

Built during a Generative AI Internship — Google Cloud Generative AI (SmartInternz).

## Features
- Upload a photo of a tablet/medicine package
- Gemini Vision analyzes the image and identifies the medication
- Returns a structured breakdown: identification, pharmacological classification, uses, and safety notes

## Tech stack
- Streamlit — web app UI
- Google Generative AI (Gemini API) — image understanding
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

## Note
Google periodically retires older Gemini model versions. If `gemini-flash-latest` in `app.py` stops working, check [Google's model list](https://ai.google.dev/gemini-api/docs/models) and swap in the current model name.

## Example
Upload a photo of a tablet box → get an AI-generated pharmaceutical profile: brand name, active ingredient, strength, classification, and uses.