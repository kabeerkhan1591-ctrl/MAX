# MAX — Neural Voice Interface

A browser-based voice assistant with a cyberpunk HUD aesthetic. Speak in **English**, **Hindi**, or **Urdu** to open apps, search the web, check the time, or ask simple questions. Fully client-side — no server, no API keys.

---

## Features

- 🎙️ **Voice Control** — powered by the browser’s Speech Recognition API
- 🌐 **Multilingual** — understands & replies in English, Hindi, and Urdu
- 🔍 **Smart Search** — strips wake words & filler so  
  `"max search location unit 5"` → searches only `"unit 5"`
- 🚀 **App Launcher** — YouTube, Google, Gmail, Maps, Spotify, WhatsApp, Instagram, Facebook
- 💻 **Cyberpunk HUD** — matrix code-rain, holographic rings, live system panels, scanlines
- 🔒 **Privacy-first** — everything runs locally in your browser

---

## Supported Commands

| Action          | Examples                                      |
|-----------------|-----------------------------------------------|
| Open app        | `open youtube`, `youtube kholo`, `یوٹیوب کھولو` |
| Search          | `search unit 5`, `max search location unit 5` |
| Time            | `what's the time`, `time kya hai`, `وقت کیا ہے` |
| Identity        | `who are you`, `tum kaun ho`                  |
| Status          | `how are you`, `kaise ho`                     |

---

## How to Use

1. Open `max-console.html` in **Chrome** or **Edge** (best speech support)
2. Allow microphone access when prompted
3. Click the center core to activate MAX
4. Speak a command
5. Click again to deactivate

---

## Tech Stack

- Pure HTML / CSS / Vanilla JS
- Web Speech API
- Canvas (matrix rain effect)
- No frameworks, no backend

---

## Browser Support

| Browser     | Voice Support |
|-------------|---------------|
| Chrome      | ✅ Excellent  |
| Edge        | ✅ Excellent  |
| Firefox     | ⚠️ Limited    |
| Safari      | ⚠️ Limited    |

---

## Notes

- Speech recognition requires an internet connection (browser sends audio to the vendor’s service)
- Works best on desktop or Android Chrome
- Does **not** send WhatsApp/Instagram messages or make calls — browsers block that for security

---

## License

MIT — free to use, modify, and share.
