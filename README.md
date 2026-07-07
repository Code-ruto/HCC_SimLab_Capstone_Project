# SimBot Launcher

A voice-interactive AI chatbot simulation application built with Python that features multiple personas and conversational AI capabilities.

## 📋 Overview

SimBot Launcher is a Python-based conversational AI application that uses voice input/output to interact with users. Built following Clean Architecture and Pragmatic Programmer principles, the application allows users to select between different personas and engage in simulated conversations.

## 🎯 Features

- **Voice Input/Output**: Integrated speech recognition and text-to-speech capabilities
- **Multiple Personas**: Choose between different conversation personalities (Number One, Number Two)
- **Clean Architecture**: Modular design separating concerns (Voice, Logic, Modules)
- **Conversational AI**: Simulated conversation engine with persona-based responses

## 🛠️ Technology Stack

- **Language**: Python 3.11+
- **Speech Recognition**: `SpeechRecognition`
- **Text-to-Speech**: `edge-tts`
- **Audio Processing**: `PyAudio`
- **HTTP Client**: `aiohttp`

## 📦 Installation

### Prerequisites

- Python 3.11 or higher
- pip (Python package manager)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Code-ruto/Final_Project.git
cd Final_Project
```

2. Create a virtual environment (recommended):
```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the application:
```bash
python main.py
```

The application will:
1. Prompt you to choose a persona ("Number One" or "Number Two")
2. Listen for your voice input
3. Process your input through the selected persona
4. Respond with voice output and continue the conversation

## 📁 Project Structure

```
Final_Project/
├── main.py                 # Application entry point
├── requirements.txt        # Python dependencies
├── Voice/                  # Voice I/O module
│   └── imports.py         # Speech recognition and TTS utilities
├── Logic/                  # Conversation logic module
│   └── conversation.py    # SimBotSimulation engine
└── Modules/               # Data and persona definitions
    └── dialog.py          # Persona definitions (SIMBOT_PERSONA, BRITTANY_PERSONA)
```

### Key Components

- **Voice Module**: Handles speech recognition and text-to-speech operations
- **Logic Module**: Contains the core conversation simulation engine
- **Modules**: Defines conversation personas and dialogue patterns

## 📋 Dependencies

Key packages used:

| Package | Version | Purpose |
|---------|---------|---------|
| SpeechRecognition | 3.14.2 | Voice input processing |
| edge-tts | 7.0.1 | Text-to-speech conversion |
| PyAudio | 0.2.14 | Audio input/output |
| aiohttp | 3.11.18 | Asynchronous HTTP requests |

See `requirements.txt` for complete dependency list.

## 🎤 Voice Commands

The application listens for:
- **"number one"** - Select the first persona
- **"number two"** - Select the second persona

## 📝 Development Notes

This project follows:
- **Clean Architecture**: Clear separation of concerns across modules
- **Pragmatic Programmer Principles**: Practical, maintainable code design

## 📄 License

No license currently specified. See GitHub repository for more information.

## 👤 Author

[Code-ruto](https://github.com/Code-ruto)

## 📞 Support

For issues, questions, or contributions, please visit the [GitHub Issues](https://github.com/Code-ruto/Final_Project/issues) page.

---

**Last Updated**: April 2026
