# jarvis-voice-assistant
# Jarvis – Voice-Controlled Virtual Assistant

This is a Python-based voice assistant named **Jarvis** that listens to voice commands and performs smart tasks using AI, APIs, and speech processing libraries.

## 🔧 Features
- Wake word detection ("Jarvis")
- GPT-3.5 powered responses using OpenAI API
- Opens websites like Google, YouTube, Facebook, LinkedIn
- Plays YouTube music using custom keywords
- Fetches latest news headlines from NewsAPI
- Converts AI responses into speech using gTTS and pygame

## 🛠️ Technologies Used
- Python
- OpenAI API (GPT-3.5)
- speech_recognition
- gTTS (Google Text-to-Speech)
- pygame (audio playback)
- webbrowser
- requests (for API calls)
- NewsAPI

## 📁 Project Files
- `main.py`: Core assistant logic – voice commands, GPT, music, and news handling
- `client.py`: Test script to query OpenAI directly
- `musicLibrary.py`: Dictionary with music keywords and YouTube links

## ▶️ How to Run
1. Install dependencies:
   ```bash
   pip install openai speechrecognition gtts pygame requests
