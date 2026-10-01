# AI-Powered Voice Assistant Using Python

An AI personal voice assistant built with Python that uses speech recognition, text-to-speech, web services, and APIs to perform common voice-controlled tasks.

## Features

- Speech-based interaction using SpeechRecognition
- Text-to-speech responses using pyttsx3
- Opens YouTube, Google, Gmail, and Stack Overflow
- Provides the current time
- Fetches headlines from Times of India
- Captures a photo using the camera
- Performs web searches
- Retrieves short Wikipedia summaries
- Answers computational and geographical questions using WolframAlpha
- Retrieves weather information using OpenWeatherMap
- Can log off the Windows PC
- Provides a voice response describing available capabilities

## Technologies

- Python
- SpeechRecognition
- pyttsx3
- Wikipedia API/library
- OpenWeatherMap API
- WolframAlpha API
- eCapture
- Requests

## Project Structure

```text
AI-Powered-Voice-Assistant/
├── voice_assistant.py
├── requirements.txt
├── .env.example
├── .gitignore
├── AI-FINAL.png
└── README.md
```

## Setup

1. Install Python.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file from `.env.example`.
4. Add your own OpenWeatherMap and WolframAlpha API credentials to `.env`.
5. Run:

```bash
python voice_assistant.py
```

## API Configuration

The project uses environment variables for API credentials. **Do not commit your `.env` file or API keys to GitHub.**

```text
OPENWEATHER_API_KEY=your_key
WOLFRAM_APP_ID=your_app_id
```

## Notes

This project was developed as a Python-based AI voice assistant demonstrating speech recognition, natural-language interaction, API integration, and desktop/web automation.
