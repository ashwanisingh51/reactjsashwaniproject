

## 🚀 Features

✅ Text-based Utilities
✅ Audio Upload and Transcription (using Whisper API or custom backend)
✅ Summarize Long Texts Automatically
✅ Convert Text to UPPERCASE / lowercase / Title Case
✅ Count Words and Characters
✅ Remove Extra Spaces
✅ Copy to Clipboard
✅ Dark/Light Mode Toggle
✅ Alert Notifications
✅ Fast, Responsive UI

---

## 📷 Demo

> Add a link here if deployed
> [https://textutils-demo.netlify.app](https://textutils-demo.netlify.app)

![screenshot](link_to_screenshot)

---

## ⚙️ Tech Stack

| Frontend  | Backend (optional) | AI/ML                         |
| --------- | ------------------ | ----------------------------- |
| React.js  | Python Flask       | OpenAI Whisper / Transformers |
| Bootstrap | Flask REST API     | HuggingFace (optional)        |

---

## 📁 Project Structure

```
textutils/
├── public/
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── TextForm.js
│   │   ├── AudioUploader.js
│   │   └── Alert.js
│   ├── App.js
│   └── index.js
├── backend/ (optional)
│   └── app.py (Flask backend)
├── requirements.txt (for backend)
├── README.md
└── package.json
```

---

## 🔧 Setup Instructions

### 👉 Frontend (React)

```bash
git clone https://github.com/your-username/textutils.git
cd textutils
npm install
npm start
```

> Open your browser at `http://localhost:3000`

---

### 👉 Backend (for Audio Transcription)

```bash
cd backend
pip install -r requirements.txt
python app.py
```

> Backend runs on `http://localhost:5000`

---

## 📦 Backend `requirements.txt` (Python)

```
Flask==2.3.3
flask-cors==4.0.0
openai-whisper==20231117
transformers==4.41.1
torch==2.3.0
pydub==0.25.1
```

> Or use any other ASR / summarizer model of your choice

---

## 🧪 Example Use Cases

| Feature             | Input Example    | Output                   |
| ------------------- | ---------------- | ------------------------ |
| UPPERCASE           | `hello world`    | `HELLO WORLD`            |
| Audio Transcription | `.mp3/.wav` file | `The quick brown fox...` |
| Summarization       | Long paragraph   | One-sentence summary     |
| Remove Extra Spaces | `Hi     there`   | `Hi there`               |

---

## 🌐 Deployment (Frontend)

You can deploy to:

* [Netlify](https://www.netlify.com/)
* [Vercel](https://vercel.com/)
* GitHub Pages via `gh-pages`

---

## 🛠️ Future Improvements

* 📌 Voice-to-text with live mic input
* 📌 Save and share text summaries
* 📌 Multilingual support
* 📌 Grammar checker integration

