# HelpDesk2_AI
After weeks of building and refining, I’m excited to share a quick glimpse of Helpdesk AI, my personal voice assistant project powered by: ✅ Streamlit – for a clean, interactive chat-style UI ✅ Cohere API – for human-like responses and Q&amp;A 
# 🎙️ Helpdesk AI – Voice Assistant (Streamlit + Cohere)
Helpdesk AI is a smart and simple voice assistant built using **Python**, **Streamlit**, **Cohere API**, and **OpenWeather API**. It can chat, answer your questions, open/close apps, report weather, and more — all through **voice or text** commands, in a colorful chat-style web interface.

## 🚀 Project Overview

Helpdesk AI acts like a personal assistant you can talk to. It's built for desktops and runs in a browser using Streamlit. You can **speak or type** your commands, and it responds using **text and voice**. It understands natural language (powered by Cohere) and can perform real actions on your computer.

## ✨ Features

- 🗣️ **Voice & Text Input** – Speak or type your messages.
- 🧠 **AI Conversations** – Ask anything using Cohere's powerful language model.
- ☁️ **Weather Reports** – Get real-time weather updates using OpenWeather API.
- 💻 **App Control** – Open or close apps like YouTube, Notepad, VS Code, Chrome, etc.
- 🌍 **Language Detection & Translation** – Detects language and translates to English.
- 🔈 **Speech Output** – Assistant speaks responses aloud (using gTTS).
- 🧼 **Clear Chat** – Reset chat anytime.
- 📶 **Internet Check** – Informs if you’re offline.
- 🎨 **Colorful UI** – Chat-like interface with user/bot message bubbles.

---

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/helpdesk-ai.git
   cd helpdesk-ai
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Set API keys in code (already added):
Cohere API Key
OpenWeather API Key
Run the app:
bash
Copy
Edit
streamlit run app.py
### 🧠 Usage
Speak or type in the input box.
Try commands like:
"weather in Delhi"
"open YouTube" / "close Notepad"
"what is AI?"
Enable "Speak Responses" in the sidebar to hear voice replies.
Press "Speak Now" in the sidebar to use your microphone.

### ✅ Result
The assistant listens or reads your query.
It processes the command using Cohere, OpenWeather, or local system commands.
It responds in the chat and optionally speaks out loud.
Chat history is displayed in a clean, modern layout.

### 🧾 Conclusion
Helpdesk AI is a powerful yet lightweight desktop voice assistant. It uses the latest AI and voice tools to make your system interactive and user-friendly. You can expand it by adding more app controls, custom memory, or task integrations.
Built with ❤️ using Streamlit, Cohere, OpenWeather, gTTS, and Python.
📄 License
This project is licensed under the MIT License.

### ✅ What to do next:

- Save this as `README.md` in your project folder.
- Add a `screenshot.png` of your app running (optional but recommended).
- Push to GitHub:
  ```bash
  git add README.md
  git commit -m "Add project README"
  git push origin main
