# 🗯️ SavageSpeaker – Roast & Compliment Generator Bot 🔥💖

**SavageSpeaker** is an interactive Python app that lets you *roast* or *compliment* your friends (or enemies) with style. Switch modes based on your mood, and let the bot choose the perfect burn or boost — optionally read aloud using Text-to-Speech!

---

## 🌟 Features

- 🎯 Roast or Compliment Mode — based on mood or input
- 🧠 Smart Sentiment Detection (TextBlob-powered)
- 🔀 Random mode for quick burns or sweet surprises
- 🎙️ TTS Audio playback using `gTTS`
- 🧾 Roast + Compliment banks (50+ each)
- 🎛️ Mirror Mode for self-roasts / compliments
- 🖼️ Ready to integrate with GIPHY or a GUI

---

## ⚙️ How It Works

1. **Choose Mode**:  
   Select whether you want a 🔥 Roast or 💖 Compliment. Optionally turn on Mirror Mode to direct it at yourself.

2. **Input Text** (or hit Random):
   - Say anything — the app analyzes the sentiment using TextBlob.
   - Or click “Surprise me” for a random roast/compliment.

3. **Result**:
   - You’ll get a funny, biting roast or an uplifting compliment.
   - Audio plays using gTTS (Text-to-Speech).

---

## 🗂️ Project Structure

| File / Folder         | Purpose                                         |
|----------------------|-------------------------------------------------|
| `app.py`             | Streamlit app UI and response logic             |
| `roast_engine.py`    | Roast logic with sentiment detection            |
| `compliment_engine.py` | Compliment logic with TTS                      |
| `roast_bank.py`      | Collection of positive/neutral/negative roasts  |
| `compliment_bank.py` | Compliments and comforting responses            |
| `requirements.txt`   | Python dependencies                             |
| `README.md`          | This guide 🚀                                   |

---

## 💻 Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DadeJahnavi/SavageSpeaker.git
   cd SavageSpeaker

## 🌐 Live Demo

🔗 **Try the App Here:** [SavageSpeaker Web App](https://savagespeaker.streamlit.app/)

> 💬 *"Because sometimes... a little sass says it best!"*

🛠 Built with:  
**Python**, **Streamlit**, **OpenAI API**, and **Natural Language Processing (NLP)**
