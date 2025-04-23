# StudyScribe

**Your smart assistant for turning lectures into notes and notes into audio**

StudyScribe is an open-source Python tool built especially for students. With StudyScribe, you can:

- **Transcribe** lecture recordings (MP3/WAV) into clean, editable text.  
- **Synthesize** your notes into audio files (MP3) for hands-free review.  
- **Work 100% offline**, with no proprietary dependencies or fees.  
- **Choose** between OpenAI Whisper or lightweight Vosk models to balance accuracy and speed.

## 🚀 Key Features

- **High-quality ASR** powered by OpenAI Whisper, or switch to the lean Vosk engine for faster, low-resource transcription.  
- **Native TTS** using pyttsx3 (with optional Coqui TTS for more natural voices).  
- **Intuitive CLI**:
  ```bash
  # Transcribe audio to text
  sound2text transcribe lecture.mp3 --model small --output notes.txt

  # Convert text to audio
  sound2text synthesize notes.txt --output review.mp3
