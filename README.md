# AI-Short-Video-Script-Generator-DELUXE-And-Chatbot

# 🎬 AI Short Video Script Generator DELUXE + 🤖 Chatbot

Create viral short-form video scripts in seconds with AI — complete with voiceovers, PDF downloads, and a built-in Gemini chatbot to assist with content creation.

![Streamlit UI Screenshot](screenshot.png) <!-- Add your own screenshot if available -->

---

## 🚀 Features

- 🎯 **Script Generation**: Just enter a topic and get a short, punchy script perfect for TikTok or YouTube Shorts.
- 🔊 **Voiceover**: Auto-generate an English MP3 voiceover for your script using Google Text-to-Speech (gTTS).
- 📄 **PDF Export**: Download your script as a neatly formatted PDF.
- 🧠 **Gemini Chatbot**: Ask content-related questions and get AI-powered responses.
- 💾 **Script History**: Easily track your previous script generations in the sidebar.

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) – Interactive UI
- [Google Generative AI (Gemini)](https://ai.google.dev/) – Script and chatbot generation
- [gTTS](https://pypi.org/project/gTTS/) – Text-to-speech voiceover
- [FPDF](https://pyfpdf.readthedocs.io/) – PDF generation

---

## 🔧 Installation

### 1. Clone the Repository
- git clone https://github.com/your-username/ai-video-script-generator.git
- cd ai-video-script-generator

2. Create and Activate Virtual Environment (Optional but Recommended)
- python -m venv venv
- source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install Dependencies
- pip install -r requirements.txt

6. Set Your Gemini API Key
- Set your GEMINI_API_KEY as an environment variable:

- export GEMINI_API_KEY='your_api_key_here'  # For Linux/macOS

# Or on Windows:
- set GEMINI_API_KEY=your_api_key_here
  
▶️ Running the App
- streamlit run app.py

## 📦 File Structure
├── app.py                 # Main Streamlit app
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── .env (optional)        # For storing API keys securely (not included by default)


## 💡 Usage Tips
- Use the script length slider to adjust duration (15–60 seconds).

- You can download the script as both MP3 and PDF.

- The sidebar chatbot can assist you with script ideas, improvements, or content strategy.

## 📌 Requirements
- Python 3.7+

- Gemini API Key (from Google AI Studio)

- Internet connection (for API calls and TTS)
