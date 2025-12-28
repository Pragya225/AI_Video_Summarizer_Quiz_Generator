# 🤖 AI Video Summarizer & Quiz Generator

Transform YouTube videos into comprehensive summaries and interactive quizzes using AI-powered analysis.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📋 Overview

This application leverages AI to automatically process YouTube videos and generate:

- Executive Summaries - Concise overviews of video content
- Key Takeaways - Main points extracted from the video
- Full Transcripts - Time-stamped text transcriptions
- Interactive Quizzes - Auto-generated questions to test comprehension
- Visual Analysis - OCR and diagram detection from video frames

## ✨ Features

### 🎥 Video Processing

- YouTube URL input with automatic video ID extraction
- Audio extraction and transcription using Whisper AI
- Frame extraction for visual analysis
- OCR text detection from video frames
- Diagram and chart classification

### 📊 Content Analysis

- Multimodal alignment of audio, video, and visual content
- Topic segmentation using semantic similarity
- AI-powered summarization using Groq LLM
- Automatic quiz generation with explanations

### 🎯 Quiz Modes

- Learning Mode: Get instant feedback after each question
- Test Mode: Full-screen assessment with results at completion
- Hints and detailed explanations for each question
- Progress tracking and score calculation

### 👤 User Features

- User authentication with login/signup
- Video history tracking
- Session persistence across visits
- Download summaries and transcripts

## 📖 How to Use

- Paste any YouTube URL
- Wait for processing
- View summary, transcript, and take quizzes
- Download results or save to history

## 🛠️ Tech Stack

- Python 
- Whisper AI - Audio transcription
- Groq LLM - Summary & quiz generation
- Streamlit - Web interface
- OpenCV + Tesseract OCR - Frame & OCR processing
- Sentence Transformers - Topic segmentation
- yt-dlp - YouTube download
- ngrok (public url)

## 🚀 Quick Start

- Upload to Google Colab - Open Ai_summerizer_app.ipynb
- Add API Keys to Colab Secrets (🔑 icon in sidebar):
- GROQ_API_KEY - Get from console.groq.com
- NGROK_AUTH_TOKEN - Get from ngrok.com
- Run all cells - Notebook will provide a public URL
- Sign up or Login - Use demo credentials: demo / demo123
- Enter YouTube URL and generate summary!

## 🚀 Future Improvements

- Multi-language support - Transcription and summaries in multiple languages
- PDF/DOCX export - Download formatted reports with summaries and quizzes
- Collaborative mode - Share quizzes and compete with friends on leaderboards

## 🤝 Contributing

Contributions welcome! Fork the repo and submit a pull request.

## 📝 License

MIT License - see LICENSE file for details.

## 👨‍💻 Author
Pragya
