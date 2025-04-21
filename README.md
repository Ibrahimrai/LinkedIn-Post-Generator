🚀 LinkedIn Post Generator — Fully Offline, LLM-Powered 🔒💻

This project allows you to **generate LinkedIn posts** using your own **LLaMA 2 model locally on CPU** — no API keys, no cloud, no internet needed!

🧠 Ideal for content creators, professionals, and privacy-conscious AI builders.

## 📂 Project Structure


linkedin-post-generator/
│
├── linkedin-agent/                     # 🧠 Backend - Flask + LangChain + LLaMA 2
│   ├── app.py                          # Main Flask app that runs the local API
│   ├── prompts.py                      # LangChain prompt template
│   ├── models/                         # 🔥 Place your LLaMA model (.gguf) here
│   │   └── llama-2-7b-chat.ggmlv3.q8_0.bin
│   
│
├── linkedin-extension/                 # 🌐 Chrome Extension frontend
│   ├── popup.html                      # UI for input/output
│   ├── popup.js                        # JS logic (fetch API, clipboard, memory)
│   ├── style.css                       # Styling
│   ├── icon.png                        # Extension icon
│   ├── manifest.json                   # Extension config
│   ├── content.js                      # (optional) Page content script
│   └── background.js                   # (optional) Background processing


## 💡 How It Works

- Paste your **raw content**
- Choose a **tone** (Professional / Witty / Storytelling)
- Set a **word limit**
- Press **Generate**
- A LinkedIn post will be generated **offline** using the LLaMA model!

The Chrome Extension UI lets you:
- Paste and generate posts instantly
- Copy generated post to clipboard
- Retain the last post even if popup closes
- Set custom word limits

---

## ⚙️ Built With

- 🧠 LLaMA 2 7B (Quantized `.ggmlv3.q8_0` via `ctransformers`)
- 🔗 LangChain + Flask for backend logic
- 🧩 Chrome Extension (HTML/CSS/
