# AI-Driven YouTube Shorts Automation

This project automates the full pipeline for generating YouTube Shorts from Reddit stories using a combination of n8n (workflow automation), Python scripts, and AI services like Groq, Whisper, and ElevenLabs.

### Features
- Uses Groq to generate subtitles and hooks
- Integrates with Google Drive for asset management
- FFmpeg processing to overlay gameplay footage, captions, and audio
- Uploads the final video to YouTube autonomously
- Modular design with reusable n8n workflows and Python scripts

### Tech Stack
- `n8n` for orchestration
- `Python` for video processing and TTS
- `FFmpeg` for media editing
- `Groq`, `Whisper`, `ElevenLabs` for AI-enhanced content

### Purpose
Built this project to explore intelligent automation and AI-driven content creation. Aimed at reducing manual editing time while improving consistency across short-form videos.
