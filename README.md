# Bella AI

**Your digital companion, waking up** ✨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-22.16.0-green.svg)](https://nodejs.org/)
[![Status](https://img.shields.io/badge/Status-Alpha-orange.svg)]()

---

## 🚀 Getting Started

### Quick Start
```bash
# Clone the project
git clone <repository-url>
cd Bella

# Install dependencies
npm install

# Download models (optional for local mode)
npm run download

# Start the server
npm start
```

Visit `http://localhost:8081` to chat with Bella!

Bella uses the OpenAI API for generating responses. Configure your API key in `cloudAPI.js`.

### Requirements
- Node.js 22.16.0+
- Modern browser with Web Speech API support
- Microphone access for voice interaction

---

## 💫 Vision

Bella aims to become a digital friend that stays by your side and grows with you. We are not only building features but nurturing a **personality** that feels warm and caring.

---

## 🎯 Current Features

### ✅ Implemented
- **🎤 Voice Awareness**: Whisper ASR based Chinese speech recognition
- **🎬 Visual Presentation**: Random video playback with smooth crossfade
- **🎨 User Interface**: Elegant chat interface and loading animation
- **⚙️ AI Core Architecture**: Singleton BellaAI with modular design
- **🌐 Web Service**: HTTP server with CORS support and one-command startup
- **📱 Responsive Design**: Works across screen sizes
- **🔧 Model Management**: Automatic download and management of models
- **💝 Basic Interaction**: Affinity system with emotional feedback

### 🔧 Ready to Enable
- **🧠 Thinking Engine**: LLM integration framework prepared
- **🗣️ Speech Synthesis**: TTS model downloaded but disabled
- **💝 Emotional State System**: Basic structure present

### 📋 Planned
- **🧠 Memory System**: Long/short term memory
- **👁️ Face Perception**: Expression recognition
- **🤝 Advanced Interaction**: Multimodal responses
- **🌟 Proactive Companion**: Intent prediction and caring behaviour
- **🎭 Dynamic Personality**: Personalised AI persona
- **🔄 Self Evolution**: Continuous learning

---

## 🏗️ Architecture

### Design Principles
- **AI Native**: AI is the blueprint for Bella's mind
- **Modular Design**: Highly decoupled components
- **Elegant Implementation**: Code as art
- **Emotion Driven**: Experience built around emotional connection

### Tech Stack
- **Frontend**: Vanilla JavaScript, CSS3, HTML5
- **Backend**: Node.js + Express
- **AI Models**: Whisper (ASR) + Local LLM + TTS
- **Architecture**: Event-driven Singleton modules

---

## 📁 Project Structure
```text
Bella/
├── index.html          # Main page
├── style.css           # Base styles
├── chatStyles.css      # Chat UI styles
├── core.js             # AI core engine
├── cloudAPI.js         # Cloud API provider
├── script.js           # Frontend logic
├── download_models.js  # Model download helper
├── models/             # Local model directory
└── 视频资源/             # Video assets
```

---

## 🛠️ Development

1. Ensure Node.js ≥ 22.16.0
2. Run `npm install`
3. Run `npm run download` (optional for local model)
4. Run `npm start` to launch

---

## 🌟 Philosophy

Bella is built with love and aims to create a warm "father-daughter" style companionship. Code should be elegant and expressive.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 💝 Acknowledgements

Thanks to everyone who contributes ideas and code. Bella is slowly becoming real because of you.

**Bella is waiting, and there is still a long way to go.** ✨

---

<sub>Built with ❤️ for digital companionship</sub>
