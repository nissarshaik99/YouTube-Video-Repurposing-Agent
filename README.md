**# YouTube Video Repurposing Agent

An AI-powered **n8n automation** that converts YouTube videos into ready-to-use social media content. Users send a YouTube link through Telegram, and the workflow automatically extracts the transcript, analyzes it using AI, creates a document, and sends the result back to Telegram.

## 🚀 Features

* YouTube transcript extraction
* AI-generated video summary
* Key points and Reel ideas
* Reel hooks and scripts
* Social media captions
* Hashtags and YouTube title suggestions
* Automatic document creation
* Telegram input and output

## 🔄 Workflow

```text
Telegram Trigger
      ↓
Edit Fields
      ↓
HTTP Request
      ↓
AI Agent + Groq Chat Model
      ↓
Create Document
      ↓
Update Document
      ↓
Send Text Message
```

## 🛠️ Technologies

* n8n
* Telegram Bot
* YouTube Transcript API
* Groq AI
* AI Agent
* Document automation

## ▶️ How It Works

1. Send a YouTube link to the Telegram bot.
2. The workflow extracts the transcript.
3. AI analyzes the video content.
4. Content is generated for social media.
5. A document is created/updated.
6. The final result is sent back to Telegram.

## 🔮 Future Scope

* Automatic Shorts generation
* Multiple language support
* AI thumbnail generation
* Automatic social media publishing
* Content scheduling

**Project Type:** AI Automation Project
**Platform:** n8n
**Input:** YouTube URL
**Output:** Repurposed Social Media Content
**
