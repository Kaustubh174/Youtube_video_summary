# YouTube Podcast Summarizer with Whisper and GPT-3.5 Turbo

## Introduction

YouTube Podcast Summarizer is a Python script that converts long podcasts or any YouTube audio into concise summaries using OpenAI's Whisper for transcription and GPT-3.5 Turbo for summarization. The script downloads audio from YouTube, transcribes it into text, and then generates a summarized version. This tool is especially useful for individuals who want to quickly understand the content of lengthy podcasts without watching or listening to the entire recording.

## Features

- **YouTube Audio Downloading**: Downloads the audio from any YouTube video link.
- **Audio Transcription**: Converts the downloaded audio into text using Whisper.
- **Text Summarization**: Summarizes the transcribed text into a concise and informative summary, highlighting key points and providing a structured overview with GPT-3.5 Turbo.

## Usage

1. **Download Audio from YouTube**: The script checks for a valid YouTube link and downloads the audio.
2. **Transcribe Audio**: Converts the downloaded audio file into text using Whisper.
3. **Summarize Text**: Generates a summary of the transcribed text, providing an overview of the key points discussed in the podcast.

## Requirements

- Python 3.x
- pytube
- os
- re
- OpenAI API (for transcription and summarization)

## How to Run

1. Replace `'YOUR_OPENAI_API_KEY'` with your actual OpenAI API key.
2. Run the script in your Python environment.
3. The script will print the summary of the podcast.
