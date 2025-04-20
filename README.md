# SportDesk – Automated NBA Highlight Generator

**SportDesk** is a fully automated system that generates short, engaging highlight recap videos for every NBA game — updated daily and optimized for TikTok, YouTube Shorts, and Instagram Reels.

> _“Like 90s Highlight Shows. 60 seconds long and built by one person using AI and automation.”_

---

## 🔥 What It Does

After every NBA game finishes, SportDesk:
- ⏱️ Pulls game data via the NBA API
- 🧠 Generates a highlight script using LLMs (GPT-4, Claude)
- 🎙️ Creates dynamic voiceovers via ElevenLabs
- 🎬 Crops and stitches real highlight clips using FFmpeg
- 🎨 Adds a branded intro/outro with host commentary and catchphrases
- 📱 Formats everything for social media and posts daily

---

## 🎯 Platforms

Catch the content here:
- [YouTube – SportDeskNBA](https://www.youtube.com/@SportDeskNBA)
- [TikTok – @sportdesknba](https://www.tiktok.com/@sportdesknba)
- [Instagram – @sportdesknba](https://www.instagram.com/sportdesknba/)

---

## ⚙️ Stack (High-Level)

- **Python** – end-to-end orchestration
- **OpenAI & Claude** – highlight script generation
- **ElevenLabs** – text-to-speech voiceover
- **NBA API** – game data and box scores
- **FFmpeg** – highlight editing, cropping, and rendering
- **Gradio** – local UI to choose voice styles and preview scripts
- **Custom Personalities** – AI hosts with distinct tones, catchphrases, and delivery

---

## 🤖 Why I Built This

I wanted quick NBA recaps with personality — not 10-minute YouTube videos with clickbait thumbnails or robotic auto-uploads. Since I couldn't find what I wanted, I built it myself. Everything from data to voice to video is handled through a custom pipeline I’ve been fine-tuning since January 2025.

---

## 🛑 Source Code

This is a closed-source project, but I’m happy to talk about the architecture, automation, and creative process.

---

## 📩 Contact

If you're curious about the project, want to chat automation + AI + sports, or have ideas for collaboration, hit me up LinkedIn.

---

**Built and maintained by one obsessed NBA fan.**
