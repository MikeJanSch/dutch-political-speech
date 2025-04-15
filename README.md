# dutch-political-speech
# 🇳🇱 Dutch Political Speech Recognition & Analysis

This project performs automatic speech recognition (ASR) and linguistic analysis on Dutch political speeches. It scrapes YouTube, transcribes with Whisper and VOSK, evaluates model accuracy, and analyzes named entities, topics, and lexical features.

---

## 🔍 Project Goals
- Collect Dutch political speeches under 10 minutes
- Transcribe using **Whisper** and **VOSK**
- Compare ASR models via **WER**, **WIL**, **WPM**
- Enhance VOSK using custom Dutch corpus
- Analyze text via NER, topic modeling, TF-IDF, and lexical trends

---

## 🧱 Project Structure
dutch-political-speech/
│
├── data/
│   ├── raw/                 # downloaded video files (if needed)
│   ├── metadata/            # YouTube metadata
│   ├── transcripts/         # Whisper and VOSK transcriptions
│   └── evaluation/          # ASR comparison metrics
│
├── src/
│   ├── scrape_youtube.py
│   ├── whisper_transcribe.py
│   ├── vosk_transcribe.py
│   ├── compare_asr.py
│   ├── nlp_analysis.py
│   └── visualize.py
│
├── notebooks/
│   └── exploratory.ipynb
├── requirements.txt
└── README.md

