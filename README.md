# Project Ziggy: H.A.I. (Home Artificial Intelligence)

> *Built for the Edge. Born on the Legion Go.*

## 🌟 The Vision (The "Outcome")
Ziggy is not a chatbot. She is a **High-Performance Offline Assistant** designed to be an extension of the user.
*   **Zero Fluff**: Responses are fast, precise, and human-like. No "As an AI model" lectures.
*   **Zero Cloud**: 100% private. Your data never leaves the device.
*   **Zero Latency**: Optimization > Scale.

## 🦾 The Body (Hardware Target)
**Device**: Lenovo Legion Go
*   **APU**: AMD Ryzen Z1 Extreme (8-Core/16-Thread, AI-ready).
*   **Storage Strategy**:
    *   **OS/Core**: 1TB NVMe SSD (Fast retrieval).
    *   **Long-Term Memory**: 1TB SD Card (Archival conversations & logs).
*   **Constraints**: Power efficiency and thermal management. Ziggy must sleep when not needed.

## 🧠 The Stack (Architecture)
We use a modular "limbs" system to ensure upgradability.

| Limb | Technology | Role | Optimization Strategy |
| :--- | :--- | :--- | :--- |
| **Brain** | **Ollama** (Llama 3 / Phi-3) | Decision making & Personality. | **Quantization**: 4-bit/5-bit models to maximize token/sec on the Z1 GPU. |
| **Ears** | **Vosk** | Wake-word detection ("Hey Ziggy"). | **Low-Power**: Runs on CPU efficiency cores to save battery while listening. |
| **Mouth** | **pyttsx3** (SAPI5) | Immediate voice feedback. | **Zero-Latency**: Uses native Windows engine No network delay. |
| **Nerves** | **Python** | The glue code. | **Asynchronous**: Non-blocking I/O for instant reaction times. |

## 🕹️ Capabilities Roadmap

### Phase 1: The Foundation
*   [ ] **Wake Word**: Reliable activation on "Hey Ziggy".
*   [ ] **Voice Loop**: Listen -> Transcribe -> Decide -> Speak.
*   [ ] **Personality**: Witty, concise female persona.

### Phase 2: System Integration ("Jarvis Mode")
*   [ ] **App Control**: Launch games (Steam/Game Pass) via voice.
*   [ ] **Hardware Control**: Toggle TDP modes, adjust volume, check battery status.
*   [ ] **Media**: "Pause music", "Next track".

### Phase 3: Advanced Cognitive Features
*   [ ] **Compression Memory**: Summarize conversations daily and move to SD card storage to keep context without bloating RAM.
*   [ ] **RAG (Knowledge)**: Index local documents so Ziggy can answer questions about your files.

## 🚀 Quick Start (The "Download")
1.  **Flash**: Install fresh Windows 11 (Debloated).
2.  **Install**: Ollama Windows Preview.
3.  **Run**: `ollama pull phi3`
4.  **Clone**: This repo.
5.  **Wake**: Run `python main.py`.

---
**Status**: Design Phase.
**Next Step**: Implementation of Phase 1.
