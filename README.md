# Mandy Web 👩‍💻

Chat with **Mandy** — a personal AI assistant — directly in any browser.

**Live URL:** https://avanderberg48-collab.github.io/mandy-web/

## Features
- 💬 **Text chat** — shows the real shared conversation (same as WhatsApp), auto-updates every 10 seconds
- 🎤 **Voice notes** — record and send; Mandy receives them as attachments
- 📞 **Hands-free calls** — speak naturally; Mandy answers out loud (Web Speech API)
- 📎 **Attachments** — send any file
- 🔊 **Spoken replies** — toggle to hear every reply read aloud; tap any message to hear it
- 🔒 **PIN lock** — personal privacy gate

## Tech
Single self-contained HTML page (no build step). Talks directly to the Base44 Agent API with full CORS support. File/voice uploads go through a Base44 backend function for permanent CDN hosting.

Deployed via GitHub Pages from the `main` branch.
