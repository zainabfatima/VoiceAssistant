# 🌍 Multi-lingual Voice Assistant 🎙️🤖

This project is a real-time **voice assistant** that listens to your speech, converts it to text using **Whisper (OpenAI)**, generates a language-specific reply using **GPT-3.5**, and speaks the response out loud using **ElevenLabs Text-to-Speech** — all in the language of your choice!

---

## 🧠 Features

- 🎤 Records your voice live
- 📝 Converts speech to text via **OpenAI Whisper**
- 🌐 Understands and responds **in any language you choose**
- 💬 Replies using **OpenAI GPT-3.5 Turbo**
- 🔊 Speaks the assistant’s response using **ElevenLabs TTS**
- 🧽 Automatically deletes old recordings
- 🔁 Works in a loop — continue talking or exit anytime

---

## 📁 Project Structure

Multi-lingual-voice-assistant-/
├── main.py # Main file to run the assistant loop
├── whisper.py # Handles audio transcription using Whisper API
├── record.py # Records audio from microphone and saves it
├── tts_elevenLabs.py # Text-to-speech using ElevenLabs voice API
├── requirements.txt # Required libraries
├── .env # Contains API keys (OpenAI and ElevenLabs)
└── recordings/ # Temporary folder for storing user audio

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/moaaz12-web/Multi-lingual-voice-assistant-.git
cd Multi-lingual-voice-assistant-
