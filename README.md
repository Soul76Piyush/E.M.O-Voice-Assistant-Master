# 🤖 E.M.O-Voice-Assistant-Master - Your Personal Desktop AI Assistant
Meet **E.M.O** — a Python-powered voice assistant designed to make your daily tasks easier and more interactive! This AI assistant comes with a sleek GUI, voice command support, and integrates multiple APIs to provide real-time information, automate tasks, and entertain you.

---

## ✨ Features

JARVIS can do a wide range of amazing things:

- 🗣️ Greet you
- ⏰ Tell the current time and date
- 🚀 Launch installed applications or software
- 🌐 Open websites
- 🌦️ Provide real-time weather info of any city
- 📍 Show location and distance to any place
- 💻 Display system status (RAM, CPU, Battery)
- 📅 Access your Google Calendar events
- 🧠 Answer queries using Wikipedia or WolframAlpha
- 🔍 Search anything on Google
- 🎵 Play songs on YouTube or offline
- 🗞️ Read top headlines (Times of India)
- 📧 Send emails with subject and content
- ➗ Calculate complex expressions
- 📓 Take notes in Notepad
- 😂 Tell random jokes
- 🌐 Show your IP address
- 🔄 Switch between open windows
- 📸 Take and save screenshots with custom names
- 🔐 Hide/unhide files in a folder
- 🖼️ Clean, intuitive Graphical User Interface

---

## 🎥 Demo

▶️ **Check out the working demo** on YouTube: [Watch Video](https://www.youtube.com/watch?v=oKtrHy0ERNA)

---

## 🔑 API Keys Required

You need the following API keys to unlock the full potential of JARVIS:

- 🌦️ [OpenWeatherMap API](https://openweathermap.org/api)
- 📊 [WolframAlpha API](https://www.wolframalpha.com/)
- 🗓️ [Google Calendar API](https://developers.google.com/calendar/auth)

---

## ⚙️ Installation Guide

Follow the steps below to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Jarvis-Voice-Assistant.git
cd Jarvis-Voice-Assistant
````

### 2. Create and Configure `config.py`

In `Jarvis/config/config.py`, add:

```python
weather_api_key = "<your_api_key>"
email = "<your_email>"
email_password = "<your_email_password>"
wolframalpha_id = "<your_wolframalpha_id>"
```

### 3. Create Python Environment (Using Anaconda)

```bash
conda create -n jarvis python==3.8.5
conda activate jarvis
```

### 4. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 5. Install PyAudio (If Not Working)

Refer this solution for PyAudio wheel files: [Install PyAudio](https://stackoverflow.com/a/55630212)

### 6. Run the Project

```bash
python main.py
```

Enjoy using your personal assistant! 🎉

---

## 🗂️ Project Structure

```plaintext
├── driver/
├── Jarvis/
│   ├── config/         # Secret API keys and credentials
│   ├── features/       # All features implemented modularly
│   └── utils/          # GUI images and assets
├── __init__.py         # Feature imports
├── gui.ui              # GUI layout file
├── main.py             # Main execution script
├── requirements.txt    # Required dependencies
└── README.md           # Project Documentation
```

---

## 🧩 Adding New Features

JARVIS is highly **modular and extensible**:

1. Create a new `.py` file inside the `features/` directory.
2. Define your feature function.
3. Import your function inside `__init__.py`.
4. Add a voice trigger for the feature in `main.py`.

---

## 💡 Future Improvements

* Voice training personalization
* Integration with home automation (IoT)
* Task scheduling and reminders
* Multi-language support
* More API integrations

---

## 🙌 Acknowledgements

* Python libraries: `speech_recognition`, `pyttsx3`, `pywhatkit`, `wikipedia`, `wolframalpha`, etc.
* APIs: OpenWeather, WolframAlpha, Google Calendar
* [StackOverflow](https://stackoverflow.com/) for invaluable help

---


## 🔗 Connect

For feedback or contributions, feel free to [open an issue](https://github.com/your-username/Jarvis-Voice-Assistant/issues) or submit a PR.

---

> "I'm not just a voice... I'm your virtual companion!" — JARVIS

```

---

Let me know if you’d like me to also create a **GUI preview image**, **custom logo**, or help with **publishing your project** on GitHub Pages or PyPI.
```


## Future Improvements
- Generalized conversations can be made possible by incorporating Natural Language Processing
- GUI can be made more nicer to look at and functional
- More functionalities can be added
