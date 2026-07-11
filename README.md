# 🎬 AI Video Assistant

An AI-powered video analysis application that converts video/audio into meaningful insights using speech recognition, summarization, and Retrieval-Augmented Generation (RAG). The application supports uploading audio files or processing YouTube videos, generates transcripts, creates summaries, extracts important information, and allows users to ask questions about the content.

---

## ✨ Features

* 🎥 Process YouTube videos
* 🎙️ Upload audio files
* 📝 Automatic speech-to-text transcription using Whisper
* 🌐 Hindi to English translation support
* 📄 AI-generated meeting/video summaries
* 📌 Extract key decisions
* ✅ Extract action items
* ❓ Identify important questions
* 🔍 Ask questions about the transcript using RAG
* 📥 Export results as PDF or text
* 💻 Interactive Streamlit interface

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### AI & Machine Learning

* OpenAI Whisper
* LangChain
* Mistral AI
* Sentence Transformers
* ChromaDB

### Supporting Libraries

* yt-dlp
* PyTorch
* Hugging Face
* Deep Translator
* ReportLab
* FPDF
* FFmpeg

---

## 📂 Project Structure

```text
AI-Video-Assistant/
│
├── app.py
├── main.py
├── Requirements.txt
│
├── core/
│   ├── extractor.py
│   ├── rag_engine.py
│   ├── summarizer.py
│   ├── transcriber.py
│   └── vector_store.py
│
├── utils/
│   └── audio_processor.py
│
└── test.py
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Video-Assistant.git
```

```bash
cd AI-Video-Assistant
```

### 2. Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r Requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and add your API key.

```text
MISTRAL_API_KEY=your_api_key_here
```

### 5. Install FFmpeg

Install FFmpeg and ensure it is added to your system PATH.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🚀 How It Works

1. Upload an audio file or provide a YouTube video URL.
2. Audio is extracted and processed.
3. Whisper converts speech into text.
4. Optional translation converts Hindi speech to English.
5. AI generates:

   * Transcript
   * Summary
   * Key Decisions
   * Action Items
   * Questions
6. The transcript is stored in a vector database.
7. Users can ask natural language questions about the content.
8. Results can be exported as PDF or text.

---

## 📦 Dependencies

Some major libraries used in this project include:

* streamlit
* openai-whisper
* torch
* langchain
* langchain-community
* langchain-mistralai
* chromadb
* sentence-transformers
* yt-dlp
* deep-translator
* reportlab
* python-dotenv

---

## 📸 Future Improvements

* Speaker diarization
* Multiple language support
* Timestamp-based summaries
* Chat history
* Cloud deployment
* Real-time meeting transcription
* User authentication

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is intended for educational and learning purposes. You may modify and extend it according to your needs.

---

## 👩‍💻 Author

**Rakshita Handage**

If you found this project useful, consider giving it a ⭐ on GitHub.
