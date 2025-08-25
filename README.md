# 🧩 Dyslexia Assist - Chrome Extension

Dyslexia Assist is a *Chrome extension* designed to help users with *dyslexia* read and understand text more easily.  
It provides *text simplification* and *text-to-speech (TTS)* functionalities directly on any website.  
The system also includes a *backend server* to store *user preferences, manage authentication, and handle API calls* for text simplification and TTS.

---

## 📌 Features

### *🔹 Chrome Extension*
- *Right-Click Menu Integration*  
  - Select any text → Right-click → Choose:
    - *Simplify Text* → Shows an easier, elementary-level version of the selected text.
    - *Read Aloud (TTS)* → Streams natural audio for the selected text.
- *Floating TTS Controls*  
  - Pause, resume, and stop audio directly beside the highlighted text.
- *Simplified Text Modal*  
  - Displays simplified text in a *clean, distraction-free, dyslexia-friendly modal*.
- *Font Customization*  
  - Uses *OpenDyslexic font* for better readability.
- *Dark/Light Mode Support* (optional future enhancement)

### *🔹 Backend Server*
- *User Authentication* → Signup, Login, Logout.
- *Preferences Management* → Save preferred font size, colors, and TTS voice.
- *Text Simplification* → Uses an *AI/NLP API* to simplify complex text.
- *Text-to-Speech (TTS)* → Integrates with a TTS API to stream natural voices.
- *Secure API Gateway* → All external API calls (simplification & TTS) go through the backend.

---
