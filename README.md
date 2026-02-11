🔊 Jarvis - AI-Powered Desktop Voice Assistant
Jarvis is a fully functional, voice-controlled AI desktop assistant developed in Python. With a simple voice command, Jarvis can automate your daily desktop and web tasks—ranging from playing songs and checking the weather to sending emails, running applications, retrieving summaries, and even conversing intelligently using OpenAI.

✨ Features
🎙️ Voice Interaction — Activate with "Jarvis", recognize speech and respond with natural TTS
🌐 Web Utilities — Weather, news, Wikipedia summaries, internet speed, COVID-19 stats
📩 Messaging & Mail — Send WhatsApp messages or emails via voice
🔧 System Utilities — Open/close apps, control volume, capture screenshots, set reminders
🧘 Entertainment — Play devotional/meditation music, YouTube songs, jokes, quotes, stories
🌍 Translator — Translate and transliterate between 100+ languages with script conversion
💬 AI Chat — Handles unknown queries using OpenAI's GPT-3.5-turbo model
🔒 Access Control — Password and hotword-protected for secure usage
🛠️ Technologies Used
Speech Recognition: SpeechRecognition, pyttsx3, gTTS
Media & GUI: pygame, opencv-python, tkinter, Pillow
Web & APIs: requests, pytube, wikipedia, openai, pywhatkit, speedtest-cli
Geolocation: OpenCageGeocode, geopy
Data Storage: TinyDB
Others: pycaw, smtplib, schedule, deep-translator, qrcode
🔐 Setup Instructions
1. Clone the Repository
git clone https://github.com/yourusername/jarvis-desktop-assistant.git
cd jarvis-desktop-assistant
2. Install Dependencies
Make sure Python 3.7+ is installed. Then:

pip install -r requirements.txt
3. Set API Keys
Replace the following placeholder values in the script:

YOUR-OPENAI-API-KEY
OpenWeatherMap API Key
NewsAPI Key
OpenCage API Key
You can optionally use environment variables or a .env file for better security.

4. Run Jarvis
python jarvis.py
Say "Jarvis" to activate and begin giving commands.

📁 Project Structure
jarvis/
├── music/                  # Music files for devotional/meditation
├── screenshots/            # Screenshots taken by Jarvis
├── jarvis.py               # Main Python script
├── paths.json              # App-specific launch paths
├── requirements.txt        # All required Python packages
└── README.md               # This file
✅ Supported Voice Commands
"Open YouTube", "Open Chrome"
"Send email", "Send WhatsApp message"
"Translate hello to Hindi"
"Generate QR for URL"
"What's the weather in London?"
"Play devotional song", "Start meditation"
"Tell me a joke/story/fact/quote"
"Set reminder at 08:00 AM"
"Capture screenshot/photo"
"Evaluate 5 * (2 + 3)"
... and many more!

🧑‍💻 Developed By
Ponna Chaitanya
📧 ponnachaitanya1912@gmail.com
📍 India

⚠️ Disclaimer
This project is for educational and personal use only. Some features may require stable internet and are system-specific (Windows).

📜 License
MIT License © 2026   Ponna Chaitanya
