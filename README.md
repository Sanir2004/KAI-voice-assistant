# KAI Voice Assistant

KAI is a Python-based voice assistant for desktop automation and intelligent information retrieval. It enables you to control your Mac with natural voice commands-open apps, search online, fetch news, get weather updates, and much more.

---

## ✨ Features

- **Voice-activated commands** for launching apps, searching Google/Wikipedia/YouTube, and more.
- **Fetch news headlines** and **current weather** for any city.
- **Movie info lookup** via IMDb.
- **Perform calculations and answer factual queries** using WolframAlpha.
- **Get your public IP address** instantly.
- **Conversational responses** with greetings and context-aware prompts.
- **Hotkey support**: Instantly start/pause listening using keyboard shortcuts.
- **Modular codebase**: Separate files for conversation logic and online utilities.
- **Optimized for macOS** (uses Mac-specific voice engine and app launching).

---

## 🚀 Getting Started

### Requirements

- Python 3.x
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [speech_recognition](https://pypi.org/project/SpeechRecognition/)
- [requests](https://pypi.org/project/requests/)
- [imdbpy](https://pypi.org/project/IMDbPY/)
- [wolframalpha](https://pypi.org/project/wolframalpha/)
- [pyaudio](https://pypi.org/project/PyAudio/)
- [pynput](https://pypi.org/project/pynput/)
- [wikipedia](https://pypi.org/project/wikipedia/)
- [pywhatkit](https://pypi.org/project/pywhatkit/)
- [python-decouple](https://pypi.org/project/python-decouple/)

Install all dependencies:

'''pip install -r requirements.txt'''

*(Create a `requirements.txt` file with the above packages for easy installation.)*

---

### Setup

1. **Clone the repository:**
git clone https://github.com/Sanir2004/KAI-voice-assistant.git
cd KAI-voice-assistant

2. **Configure Environment Variables:**
- Create a `.env` file in the project root:
  ```
  USER=SANIR
  BOT=KAI
  ```
- Add your API keys for [OpenWeatherMap](https://openweathermap.org/api), [NewsAPI](https://newsapi.org/), and [WolframAlpha](https://products.wolframalpha.com/api/) in the respective places in the code or `.env` as needed.

3. **Run the Assistant:**

python main.py


---

## 🗂️ Project Structure

| File         | Purpose                                              |
|--------------|------------------------------------------------------|
| `main.py`    | Core logic, voice recognition, command handling      |
| `conv.py`    | Conversation responses and random prompts            |
| `online.py`  | Online utilities: search, news, weather, YouTube     |
| `.env`       | Environment variables and API keys (not committed)   |
| `README.md`  | Project documentation                                |

---

## 🎤 Example Commands

- “Open terminal”
- “What’s the weather in Mumbai?”
- “Give me news”
- “Play [song] on YouTube”
- “Search [topic] on Wikipedia”
- “Calculate 23 times 47”
- “Tell me about the movie Inception”

---

## 🛡️ Security & Privacy

- All voice processing is done locally; no audio is sent to external servers except for online search and APIs.
- Keep your API keys secure in the `.env` file.

---

## 🙌 Credits

Created by **Sanir Singh**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Feel free to contribute, open issues, or suggest features!*
