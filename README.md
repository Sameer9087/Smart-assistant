🧠 Voice Assistant – Personal AI Assistant in Python

A personal voice assistant built with Python that listens to your voice commands and performs a variety of tasks — from playing YouTube songs and telling jokes to checking the weather, opening websites, generating QR codes, and more.

This project uses speech recognition, text-to-speech, and multiple APIs to act as your mini AI companion.

🧩 Features

✅ Voice Interaction

Recognizes your voice using speech_recognition

Responds with natural speech using pyttsx3

---

✅ Entertainment & Info

Plays YouTube songs (pywhatkit)

Tells jokes (pyjokes)

Fetches Wikipedia summaries

Answers factual questions via WolframAlpha

Reads the latest news using NewsAPI

---

✅ Utilities

Tells the current time and weather

Sends emails

Takes snapshots using your webcam (ecapture)

Generates and displays QR codes for your social media links

Opens popular websites and apps with simple voice commands

---

✅ Fun Commands

Responds to personal prompts like “I love you”, “Who created you?”, “How are you?”, etc.

---

⚙️ Requirements

Make sure you have Python 3.8+ installed.
Install the dependencies using:

pip install speechrecognition pyttsx3 pyaudio webbrowser pywhatkit datetime pyjokes wikipedia smtplib requests ecapture wolframalpha qrcode

---

⚠️ Note:

pyaudio may require extra setup on Windows. If you face errors, install it via:

pip install pipwin
pipwin install pyaudio

---

🔐 Security Notes

⚠️ Do not hard-code your real email password in the script.
Use environment variables or app passwords.

⚠️ Keep your API keys private.
If uploading this to GitHub, replace them with placeholders like "YOUR_API_KEY_HERE".

---

🪄 How It Works

When you run the script, the assistant greets you.

It listens continuously for your voice commands.

It parses the command and performs the appropriate action (open a site, play a song, tell a joke, etc.).

The assistant responds to you using text-to-speech.

---

🧑‍💻 Author

👤 Ganapurapu Durga srinath.
💬 "Designed and developed this personal assistant using Python for automation, learning, and fun!"

---
🌟 Future Improvements


Add GUI (using Tkinter or PyQt)

Add chat memory or context-based conversation

Integrate Spotify API for better music control

Add wake word detection (e.g., “Hey Jarvis”) without needing to say your name first.








