# YouTube Content Summarizer

A Streamlit-based application to extract, summarize, translate, and convert YouTube video transcripts to audio summaries.

## Features

- Extract transcript from YouTube videos
- Summarize using extractive (Gensim, SpaCy, NLTK, TF-IDF) or abstractive (T5 model) methods
- Translate summaries into multiple languages
- Convert summaries into audio using text-to-speech
- Minimal, interactive UI built with Streamlit

## Technologies Used

- Python
- Streamlit
- YouTubeTranscriptAPI
- Pytube
- Gensim, SpaCy, NLTK, TF-IDF
- Transformers (T5)
- Deep Translator
- gTTS / pyttsx3

## Setup Instructions

```bash
git clone https://github.com/leovidith/youtube-content-summarizer.git
cd Youtube-Summariser
pip install -r requirements.txt
streamlit run app.py
```
## Usage
Input a valid YouTube video URL
Choose summarization type (Extractive/Abstractive)
Select the algorithm
Set summary length and translation language
View text summary or listen to audio

