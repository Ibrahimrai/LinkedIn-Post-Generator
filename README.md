# 🚀 LinkedIn Post Generator (LLM-Powered + Chrome Extension)

A fully offline LinkedIn post generator that runs on your CPU using LLaMA-2 and LangChain — designed for privacy, speed, and total control. Ideal for content creators, professionals, and productivity hackers!

---

## 🌟 Features

- 🧠 **Local LLaMA-2 model (GGUF)**
- 🔗 **LangChain + Flask backend**
- 💬 **Tone control** — Choose from professional, witty, or storytelling
- ✍️ **Word limit** — Limit the post size as per your preference
- 📋 **Copy button** — Instantly copy post to clipboard
- 💾 **Persistent memory** — Keeps last post even if popup closes
- 🌐 **Chrome Extension frontend** — Simple, elegant UI

---

## 🛠️ Tech Stack

| Layer           | Stack                                   |
|----------------|------------------------------------------|
| Backend (LLM)   | Flask + LangChain + CTransformers       |
| Model           | LLaMA 2 7B (ggmlv3.q8_0.bin)            | You can use any other Faster LLM like mistral etc  
| Embeddings      | Sentence Transformers                   |
| Frontend        | HTML/CSS + JavaScript (Chrome Extension)|
| Storage         | chrome.storage.local                    |

---

## 🔧 Installation

### 🔹 Backend

bash
git clone https://github.com/Ibrahimrai/LinkedIn-Post-Generator-LLM.git
cd LinkedIn-Post-Generator-LLM
pip install -r requirements.txt
python app.py
