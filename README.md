# Anuj Tiwari — Creative Developer Portfolio

A cinematic, interactive developer portfolio built with React, TypeScript, Vite, Tailwind CSS, Three.js, and Google Gemini Live API.

Designed with near-black backgrounds, obsidian surfaces, electric-blue highlights, restrained warm accents, 3D perspective tilt interactions, an interactive 100-day LeetCode problem-solving tracker, real project case studies, an interactive 3D Three.js game, and real-time voice conversation powered by Gemini 3.8 Live.

---

## 🎮 New Features

### 1. Interactive 3D Game: Cyber Runner (DSA Odyssey)
- **Three.js Engine**: Built using Three.js with PBR studio lighting, `ACESFilmicToneMapping`, `RoomEnvironment` PMREM reflections, and procedural ground contact shadows.
- **Full-Viewport Game Shell**: Seamless state flow (`Title Screen` -> `Playing` -> `Pause / Victory / Game Over`) with zero website navigation clutter during gameplay.
- **Composite 8-Part Player Vessel**: Assembled from extruded bevel hull, swept aerodynamic wings, cockpit canopy, thruster exhaust with dynamic point light, ground contact shadow, and pulse shield.
- **Game Feel & Encounter Design**:
  - Clamped 60fps simulation (`Math.min(rawDt, 0.05)`)
  - 45ms simulation hitstop on heavy hazard collisions
  - Decaying camera shake with spring physics
  - Pooled particle bursts on crystal harvest & impacts
  - Procedural Web Audio synthesizer (engine, crystal chimes, hazard buzz, shield sweep) with audio mute toggle.
- **Controls**: `WASD` / `Arrow Keys` to steer, `Space` for Pulse Shield, `Esc` to Pause.

### 2. Real-Time Voice Conversation with Gemini 3.8 Live (`gemini-3.8-live`)
- **Live Voice Assistant**: Real-time two-way voice conversation powered by Google's Gemini 3.8 Live API (`gemini-3.8-live`).
- **Low-Latency Audio Streaming**: 16kHz microphone PCM stream over WebSocket to `/api/live-ws`, with 24kHz audio output playback via Web Audio API.
- **Interruption Support**: Instantly clears the audio queue when interrupted.
- **Interactive UI**: Pulsing reactive audio orb, live subtitle transcription, and suggested technical questions about BankFlow, DSA routines, and internship qualifications.

---

## 🚀 Local Development Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anujtiwari2403-alt/portfolio.git
   cd portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start full-stack development server:**
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser.

4. **Build for production:**
   ```bash
   npm run build
   ```

5. **Start production server:**
   ```bash
   npm run start
   ```

---

## 📸 Profile Photograph Asset

The authentic portrait of Anuj Tiwari wearing a black suit and white shirt is located at:
```
/public/anuj-tiwari.png
```

---

## 📄 Adding Your Resume PDF

To attach your PDF resume:
1. Place your compiled resume PDF at `/public/resume.pdf`.
2. When visitors click **Resume** or **Request Resume / Download**, the file is available for direct download.

---

## 📬 Contact & Channels

- **Email**: [anujtiwari2403@gmail.com](mailto:anujtiwari2403@gmail.com)
- **GitHub**: [github.com/anujtiwari2403-alt](https://github.com/anujtiwari2403-alt)
- **LinkedIn**: [linkedin.com/in/anuj-tiwari-4905b6335/](https://www.linkedin.com/in/anuj-tiwari-4905b6335/)
