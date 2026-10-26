# VoiceGen AI — Neural Voice Cloning & Generation Studio

> Inspired by HeyGen Voice. Built with modern Full-Stack & Generative AI architecture by **Rafia Minhaj**.

---

## 🌟 Overview
**VoiceGen AI** is an end-to-end voice cloning and neural speech synthesis application. It allows users to capture a short reference audio sample (15-30s), extract acoustic speaker embeddings, and synthesize realistic, natural-sounding voiceovers across multiple languages (English, Hindi, Urdu) with sub-second latency.

---

## 🚀 Key Features
- **One-Click Voice Cloning:** Extracts pitch, timbre, and acoustic speaker embeddings from short microphone audio clips.
- **Multilingual Neural TTS:** Synthesizes clear audio in English, Hindi, and Urdu.
- **Real-Time Visualizer:** Live waveform animation and real-time audio playback controls.
- **Microservice Backend:** High-performance async FastAPI backend ready to plug into PyTorch XTTS v2 or cloud TTS engines.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, Modern Tailwind CSS, Lucide Icons, Web Speech / Web Audio API
- **Backend:** Python 3.10+, FastAPI, Uvicorn, Pydantic
- **Audio Processing:** Speaker Embedding extraction pipeline, WAV/WebM streaming buffers

---

## 📂 Project Structure
```
voicegen-ai/
├── index.html        # Interactive Frontend Dashboard
├── main.py           # FastAPI Backend Service
├── README.md         # Architecture & Documentation
└── requirements.txt  # Python Dependencies
```

---

## 💻 How to Run Locally

### 1. Launch the Backend:
```bash
pip install fastapi uvicorn pydantic python-multipart
python main.py
```
Backend will start at: `http://localhost:8000`
Interactive Swagger Docs: `http://localhost:8000/docs`

### 2. Launch the Frontend:
Simply open `index.html` in any modern web browser (Google Chrome or Edge recommended).

---

## 👩‍💻 Author
**Rafia Minhaj**
- GitHub: [@Rafiaminhaj](https://github.com/Rafiaminhaj)
- Open Source Contributor: LangChain, HuggingFace, Mem0, ChromaDB
