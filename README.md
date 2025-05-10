# 🎬 YouTube Transcript Summary Generator

This project is a powerful tool that transcribes YouTube videos and summarizes their content using a Large Language Model (LLM). It streamlines the process of understanding long-form video content by extracting the transcript and generating concise, meaningful summaries.

## 🚀 Features

- 🔗 Accepts any public YouTube video URL
- 📄 Automatically transcribes audio into text
- 🧠 Summarizes the transcript using LLM (e.g., OpenAI GPT)
- 💡 Provides TL;DR and key points
- 💬 Built-in prompt template for custom summary styles

## 🛠️ Technologies Used

- Python
- `yt_dlp` – for downloading video audio
- `Whisper` – for transcription (OpenAI)
- `LangChain` – for prompt engineering and LLM interaction
- `OpenAI` API – for generating summaries
- `Streamlit` – for web-based user interface

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/avantika06/YouTube-Transcript-Summary-Generator.git
   cd YouTube-Transcript-Summary-Generator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your OpenAI API key in a `.env` file:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   ```

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run yt_summary.py
```

Then open the local URL provided by Streamlit in your browser.

## 🧪 Example

Paste a YouTube video URL like:
```
https://www.youtube.com/watch?v=U0s0f995w14

1. Download and transcribe the video
2. Generate a structured summary
3. Display the result in the web UI

## 📂 File Structure

- `yt_summary.py` – Main Streamlit app file
- `summarizer.py` – Uses LLM to summarize transcripts
- `requirements.txt` – Python dependencies

## 💡 Future Enhancements

- Multi-language transcription
- Sentiment analysis
- Downloadable summaries
- Topic detection and keyword extraction
