# 🔦 Lumiq — AI Navigator for the Blind

<div align="center">

![Lumiq Banner](https://img.shields.io/badge/Lumiq-AI%20Navigator-a78bfa?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyYTMgMyAwIDAgMSAzIDN2N2EzIDMgMCAwIDEtNiAwVjVhMyAzIDAgMCAxIDMtM3ptNyA5YTcgNyAwIDAgMS0xNCAwTTEyIDE5djMiLz48L3N2Zz4=)

**An AI-powered voice navigation assistant for blind and visually impaired people.**

*Lumen (Light) + Intelligence = Lumiq*

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Claude AI](https://img.shields.io/badge/Claude%20AI-Anthropic-orange?style=flat)](https://anthropic.com)
[![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat&logo=openstreetmap&logoColor=white)](https://www.openstreetmap.org)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat)](LICENSE)

</div>

---

## 🌟 About

**285 million people** are visually impaired worldwide. Most cannot travel independently. Lumiq changes that.

Lumiq is a **voice-first AI navigation web app** that helps blind and visually impaired people navigate the world safely — using real GPS, AI-powered obstacle detection via camera, turn-by-turn voice directions, and emergency SOS alerts.

> *"We're not building an app. We're building independence."*

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🎙️ **Voice Navigation** | 100% hands-free — speak your destination, hear your directions |
| 🗺️ **Real GPS + Map** | Live location tracking with OpenStreetMap (free, no API key needed) |
| 🚶 **Real Walking Routes** | Turn-by-turn walking directions via OSRM routing engine |
| 📷 **Obstacle Detection** | Claude Vision AI analyzes camera feed and warns about hazards |
| 🆘 **SOS Emergency Alert** | One voice command shares live GPS coordinates with emergency contacts |
| 🌐 **5 Indian Languages** | English · हिंदी · मराठी · தமிழ் · বাংলা |
| 🌍 **Works Everywhere** | Any city, state, or country in the world |

---

## 🛠️ Tech Stack

- **Frontend** — Vanilla HTML, CSS, JavaScript (single file, no framework)
- **AI** — [Claude API](https://anthropic.com) (claude-sonnet-4) for voice responses + obstacle detection
- **Maps** — [Leaflet.js](https://leafletjs.com) + [OpenStreetMap](https://openstreetmap.org)
- **Routing** — [OSRM](https://project-osrm.org) (free open-source routing)
- **Geocoding** — [Nominatim](https://nominatim.org) (free, no API key)
- **Voice Input** — Web Speech API (built into browser)
- **Voice Output** — Web Speech Synthesis API (built into browser)
- **GPS** — Browser Geolocation API

---

## 🚀 How to Run

No installation needed! It's a single HTML file.

1. Download `lumiq.html.html`
2. Open in **Google Chrome** on your phone or computer
3. Allow **microphone** and **location** permissions
4. Tap the mic button and say *"Take me to the hospital"*

> ⚠️ Requires an Anthropic API key for full AI features. Without it, demo fallback responses are used.

---

## 🎮 Demo Commands

Try saying these after opening the app:

```
"Navigate to railway station"
"What's around me?"
"Where am I?"
"Find me the nearest pharmacy"
"SOS"                          ← triggers emergency alert
```

Switch language by tapping the language bar:
```
🇬🇧 EN  →  English
🇮🇳 हिंदी  →  Hindi
मराठी    →  Marathi
தமிழ்    →  Tamil
বাংলা    →  Bengali
```

---

## 📱 Screens

| Screen | Description |
|--------|-------------|
| 🏠 Home | Voice mic + quick action buttons |
| 🗺️ Navigate | Live map + turn-by-turn directions |
| 📷 Camera | Real-time obstacle detection |
| 🆘 SOS | Emergency alert with live GPS |

---

## 🗺️ Roadmap

- [x] Voice-first UI (hands-free)
- [x] Real GPS navigation
- [x] OpenStreetMap integration
- [x] OSRM walking routes
- [x] Claude Vision obstacle detection
- [x] SOS with live GPS coordinates
- [x] 5 Indian language support
- [ ] Host online (Vercel/Netlify)
- [ ] Real SOS SMS via Twilio
- [ ] React Native mobile app (Android + iOS)
- [ ] Offline mode with on-device AI
- [ ] Indoor navigation support
- [ ] Smart earbuds integration

---

## 🏆 Built For

This project was built for a **hackathon** with the goal of making outdoor travel safe and independent for blind and visually impaired people across India and beyond.

**Impact:** Potentially helps 285 million visually impaired people worldwide navigate independently.

---

## 👨‍💻 Author

**shalinijadon462**
- GitHub: [@shalinijadon462](https://github.com/shalinijadon462)

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify and distribute.

---

<div align="center">

Made with ❤️ for accessibility | **Lumiq = Light + Intelligence**

⭐ Star this repo if you find it useful!

</div>
