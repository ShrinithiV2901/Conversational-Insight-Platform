Conversational Insight Platform
The Conversational Insight Platform is a web application built with Streamlit that processes audio and video files to extract actionable insights using state-of-the-art NLP and speech recognition tools.

It supports:

🎙️ Transcription of audio/video

🧠 Topic Modeling

📈 Sentiment Analysis

📊 Metadata extraction

🤖 Insight generation

❓ Question answering

🌍 Translation of transcriptions

🚀 Features
✅ File Support
Accepts .mp3, .wav, and .mp4 formats.

✅ Transcription
Uses OpenAI's Whisper for high-accuracy transcription.

✅ Topic Extraction
Uses LDA via gensim to extract key topics from conversations.

✅ Metadata
Calculates:

Duration (in seconds)

Word count

Extracted keywords using KeyBERT

✅ Sentiment Analysis
Uses vaderSentiment for sentiment scores (positive, neutral, negative).

✅ Insight Generation
Summarizes conversations using Hugging Face’s facebook/bart-large-cnn.

✅ Question Answering
Answers queries about the conversation using deepset/roberta-base-squad2.

✅ Translation
Translates the transcript to selected languages using googletrans.
