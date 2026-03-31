# CineGenesis1.0
CineGenesis AI is a next-generation offline AI filmmaking software designed to run on high-end local machines. It enables users to generate complete cinematic content including stories, characters, voices, music, scenes, and final videos — all in one unified platform.

🚀 Features
🎭 AI Story Director – Generate full movie scripts (Hollywood, Bollywood, custom genres)
🧑‍🎨 Character Generator – Create multiple characters with consistent face, dress, and identity
🎤 Voice Engine (TTS) – Multi-language voices (male, female, child, aged)
🎵 Music Generator – Mood-based soundtracks (happy, sad, horror, thriller)
🌍 Environment Generator – Background scenes, weather, lighting, cinematic setups
🎥 Video Generation Engine – Image-to-video & text-to-video pipelines
🔁 Continuity System – Face lock, voice lock, scene consistency
📦 Asset Library – Prebuilt + AI-generated assets
🧠 AI Assistants – Modular directors for each creative task

Frontend (Bolt.diy / React UI)
        ↓
Backend (Python API - FastAPI)
        ↓
AI Engines:
   - SDXL (Image Generation)
   - AnimateDiff / Video Pipeline
   - Local LLM (Story Generation)
   - TTS Engine (Voice)
   - Audio Gen (Music)

   -# Clone project
git clone https://github.com/darkadstera-cloud/CineGenesis1.0.git
cd CineGenesis1.0

# Setup Python environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start backend
python app.py

📥 Required Models

Download and place inside /models folder:

SDXL (Image generation)
AnimateDiff / Stable Video Diffusion (Video)
Local LLM (e.g. Mistral / Gemma)
TTS Model (XTTS / Bark)
Music Gen Model

🎮 Usage Flow
Create New Project
Generate Story (AI Director)
Generate Characters
Generate Environment
Assign Voices & Music
Generate Scenes (Video)
Final Render (Master AI Director)

💻 System Requirements
CPU: Ryzen / i7 or above
GPU: RTX 3060 / 4060 / 5070 Ti (Recommended)
VRAM: Minimum 8GB (12GB+ recommended)
RAM: 32GB – 64GB
Storage: 500GB+ SSD

📊 Dashboard Features
GPU usage & temperature monitoring
Performance analytics
Render tracking
Project management system

🧠 Vision

CineGenesis aims to become a fully autonomous AI film studio, enabling creators to produce Hollywood-level content directly from their local machines without relying on cloud APIs.

