<p align="center">
  <img src="assets/logo.jpg" alt="Project Beatrice V2 Logo" width="200" />
</p>

<div align="center">

# 🎙️ Project Beatrice V2 (Windows)

### Real-Time AI Voice Changer for Windows (64-bit)

[![GitHub Stars](https://img.shields.io/github/stars/satiricalguru/Beatrice-voicechanger-windows?style=for-the-badge&color=ffd700&logo=github)](https://github.com/satiricalguru/Beatrice-voicechanger-windows/stargazers)
[![Version](https://img.shields.io/badge/version-2.0.0-brightgreen?style=for-the-badge)](https://github.com/satiricalguru/Beatrice-voicechanger-windows/releases/tag/v2.0.0)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011%20(64--bit)-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/satiricalguru/Beatrice-voicechanger-windows)
[![Website](https://img.shields.io/badge/Website-project--beatrice--v2.github.io-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://project-beatrice-v2.github.io/Beatrice-website/)
[![Latency](https://img.shields.io/badge/Latency-~10ms%20Ultra--Low-brightgreen?style=for-the-badge)](https://github.com/satiricalguru/Beatrice-voicechanger-windows)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Morph your voice in real-time on Windows** with AI-powered neural voice conversion — powered by the Beatrice 2.0.0 DSP engine, achieving sub-10ms latency across 112+ built-in voices. Packaged with a native 64-bit Windows VST3 dynamic library and standalone audio runtime (`beatrice_audio.exe`).

[📥 Download Windows v2.0.0](https://github.com/satiricalguru/Beatrice-voicechanger-windows/releases/tag/v2.0.0) · [🍏 Switch to macOS Version](https://github.com/satiricalguru/Beatrice-voicechanger-mac) · [🌐 Official Website](https://project-beatrice-v2.github.io/Beatrice-website/) · [🐛 Report Bug](https://github.com/satiricalguru/Beatrice-voicechanger-windows/issues)

</div>

> ### 🌐 Multi-Platform & Official Resources
> - 🪟 **Windows Version:** **[Beatrice-voicechanger-windows](https://github.com/satiricalguru/Beatrice-voicechanger-windows)** *(This repository)*
> - 🍎 **macOS Version:** **[Beatrice-voicechanger-mac](https://github.com/satiricalguru/Beatrice-voicechanger-mac)** *(Apple Silicon M1/M2/M3/M4 & Intel DMG)*
> - 🌍 **Official Beatrice Website:** **[project-beatrice-v2.github.io/Beatrice-website](https://project-beatrice-v2.github.io/Beatrice-website/)**

---

> 🌟 **Enjoying Beatrice on Windows? If this project is helpful, please consider starring ⭐ this repository! Every star supports continued open-source development.**

---

## ✨ What's New in v2.0.0 for Windows

| 🔧 Feature / Fix | Description |
|---|---|
| 🪟 **Native Windows 64-bit DSP** | Includes compiled `beatrice_2.0.0-rc.2.dll` Windows dynamic library for high-speed ctypes interop |
| ⚡ **Standalone Audio Runtime** | Pre-packaged `beatrice_audio.exe` allows running the Python audio engine without manual Python installs |
| 🗂️ **AppData Path Migration** | Custom voice models and soundboard audio persist reliably in `%APPDATA%\beatrice-voice-changer\` |
| 🗜️ **Native ZIP Extraction** | Automatic model extraction using PowerShell fallback for 100% reliable custom voice importing |
| 🖼️ **UI Image Resolution** | Local avatars and speaker portraits resolve properly via Windows `file:///` protocols |
| 🔊 **Real-time Soundboard** | Built-in soundboard with Discord/OBS routing, volume controls, and "Hear Yourself" monitoring |

---

## 🚀 Features

<table>
<tr>
<td width="50%">

### 🎤 Voice Conversion
- **112+ voices** across 3 built-in model sets
- **Dynamic model switching** at runtime — no restart required
- Real-time DSP pipeline at **16 kHz / ~10ms latency**
- Pitch shift: **−12 to +12 semitones**
- Formant shift: **−1.5 to +1.5**
- Noise gate for background suppression
- Import **custom voice models** from ZIP archives

</td>
<td width="50%">

### 🔊 Soundboard
- Upload **WAV, MP3, FLAC** and more
- One-click playback routed directly through your virtual mic
- **Hear Yourself** monitoring mode
- Inline rename & delete
- Drag-and-drop audio importing
- Custom cover image per sound

</td>
</tr>
<tr>
<td>

### 🔧 Audio Routing
- Independent **Input**, **Output**, and **Monitor** device selection
- PortAudio-backed low-latency device enumeration
- Real-time **dB input/output level meters**
- Works seamlessly with **VB-Audio Cable** & **Voicemeeter**

</td>
<td>

### 🎨 Themes & Languages
- **6 handcrafted themes** — Obsidian, Midnight, Teal, Amber, Rose, Cyberpunk
- **Light & Dark mode** per theme
- **3 languages** — English, Japanese, Chinese
- Beautiful animated speaker selection grid

</td>
</tr>
</table>

---

## 🎭 Voice Models

| Model | Voices | Description |
|-------|--------|-------------|
| 🎌 **JVS Corpus** | 100 | Japanese Voice Corpus — wide variety of male and female voices |
| ⭐ **Official Model 1** | 4 | Tsukuyomichan, Tokinashigure, OLUNE, Fukuyomichan |
| 📼 **Classic Old TTS** | 8 | Retro synthesized speech profiles |
| 🔧 **Custom Models** | ∞ | Import your own Beatrice paraphernalia ZIPs |

---

## 📸 Screenshots

<p align="center">
  <img alt="Voice Models — JVS Corpus (100 voices) with category filters" src="assets/screenshot_voice_models.png" width="100%"/>
  <br/><sub>🎤 <b>Voice Models</b> — Browse 100+ JVS voices with animated avatars and category filters</sub>
</p>

<p align="center">
  <img alt="Soundboard — Upload and trigger audio clips" src="assets/screenshot_soundboard.png" width="100%"/>
  <br/><sub>🔊 <b>Soundboard</b> — Upload audio clips and trigger them with a single click</sub>
</p>

<p align="center">
  <img alt="Library — Featured presets and Wikimedia sound effects (Japanese UI)" src="assets/screenshot_library.png" width="100%"/>
  <br/><sub>📚 <b>Library</b> — 100+ curated sound presets with multilingual UI support (Japanese shown)</sub>
</p>

<p align="center">
 <img width="2904" height="1606" alt="image" src="https://github.com/user-attachments/assets/951329b7-41be-4ea1-8d3a-66ef4b38b330" />
  <br/><sub>⚙️ <b>Settings</b> — 6 handcrafted themes, light/dark mode, and 3 languages (Chinese shown)</sub>
</p>

---

## 📥 Installation

### Option A — Download Pre-Built Release (Recommended)

Grab the latest Windows release from the **[Releases Page](https://github.com/satiricalguru/Beatrice-voicechanger-windows/releases/tag/v2.0.0)**:

| Format | File | Details |
|---|---|---|
| 🪟 **Installer** | `Beatrice.Voice.Changer.Setup.2.0.0.exe` | Standard Windows Setup wizard with Start Menu & Desktop shortcuts |
| 📦 **Portable** | `Beatrice.Voice.Changer-2.0.0-win.zip` | Extract and run `Beatrice Voice Changer.exe` directly without installing |

> 🛡️ **Windows SmartScreen Note:**
> When opening for the first time, Windows Defender SmartScreen might display:
> *"Windows protected your PC"*.
> Click **More info** ➔ **Run anyway**. This is standard for newly published open-source releases without expensive EV code-signing certificates.

---

### Option B — Build from Source on Windows

If you want to run from source or modify the code:

```powershell
# 1. Clone the Windows repository
git clone https://github.com/satiricalguru/Beatrice-voicechanger-windows.git
cd Beatrice-voicechanger-windows

# 2. (Optional) Install Python audio dependencies if running raw python backend
pip install -r requirements.txt

# 3. Install Node.js dependencies
npm install

# 4. Launch in development mode
npm run dev

# 5. Build Windows installer and portable packages
npm run dist:win
```

---

## 🎛️ How to Use with Discord, Games & OBS

To feed your converted voice into applications like **Discord**, **Zoom**, **OBS**, or games, configure a virtual audio cable:

### Recommended Driver: VB-Audio Cable
Download and install the free **VB-CABLE Driver** from [vb-audio.com/Cable](https://vb-audio.com/Cable/).

### Setup Steps:
```
[Physical Microphone] ➔ [Beatrice Voice Changer] ➔ [CABLE Input (VB-Audio)]
                                                         │
                                                         ▼
                                                [CABLE Output]
                                                         │
                                     ┌───────────────────┴───────────────────┐
                                     ▼                                       ▼
                                 [Discord]                                 [OBS]
```

1. **Install VB-Cable** (restart PC if prompted).
2. **Open Beatrice Voice Changer**:
   - Set **Input Microphone** to your real hardware mic (e.g. `Microphone (Realtek)` or `USB Mic`).
   - Set **Output Device** to **`CABLE Input (VB-Audio Virtual Cable)`**.
3. **Configure Discord / OBS / Zoom / Game**:
   - In Discord **Settings ➔ Voice & Video ➔ Input Device**, select **`CABLE Output (VB-Audio Virtual Cable)`**.
   - Set Discord **Output Device** to your normal headphones/speakers.
4. **Monitor your Voice**:
   - In Beatrice, enable **Hear Yourself** and select your headphones as the **Monitor Device** to preview the conversion in real time.
5. **Toggle the Power Button** to go **LIVE** 🟢.

> 💡 **Tip:** Set the **Noise Gate** to `0.000` for smooth and natural conversion. If you have mechanical keyboard clicks or background noise, raise it gradually to `0.010`–`0.030`.

---

## 🎮 Controls Reference

| Control | Description |
|---|---|
| ⏻ **Power Button** | Toggle LIVE (converting voice) ↔ BYPASSED (original mic audio) |
| 🎙️ **Input Microphone** | Select your physical recording device |
| 🔈 **Output Device** | Select destination (typically `CABLE Input` for virtual mic routing) |
| 👂 **Hear Yourself** | Enable live monitoring through your headphones |
| 🚪 **Noise Gate** | Mutes sound below threshold (0.000 = off) |
| 🎵 **Pitch Shift** | Adjust vocal pitch by ±12 semitones |
| 🔠 **Formant Shift** | Change vocal tract characteristic (±1.5) |
| 🔊 **Output Volume** | Final gain multiplier (0–200%) |

---

## 🧩 Custom Voice Models

You can import any Beatrice-compatible model directly from the UI:

1. Click the **Voice Model** selector and choose **Upload Custom Model**.
2. Select a `.zip` archive containing the Beatrice model paraphernalia files.
3. The model is automatically unzipped into `%APPDATA%\beatrice-voice-changer\custom_models\` and is ready for immediate selection.

**Model directory structure:**
```
my_custom_model/
├── phone_extractor.bin
├── pitch_estimator.bin
├── waveform_generator.bin
├── embedding_setter.bin
├── speaker_embeddings.bin
├── model.toml
└── avatar.png          ← optional portrait icon
```

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                 Electron UI (Windows x64)                   │
│            index.html + index.css + renderer.js             │
│  ┌─────────────────────────┐   ┌─────────────────────────┐  │
│  │  Voice Grid (112+)      │   │  Soundboard Player      │  │
│  └─────────────────────────┘   └─────────────────────────┘  │
└──────────────────────────────┬──────────────────────────────┘
                               │ HTTP REST (127.0.0.1:5005)
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                 Audio Engine Backend                        │
│      beatrice_audio.exe (or python beatrice_audio.py)       │
│  ┌───────────────────────────────────────────────────────┐  │
│  │  PortAudio Windows I/O (sounddevice)                  │  │
│  │  Beatrice VST3 ctypes wrapper (beatrice_loader.py)    │  │
│  │  Phone Extractor → Pitch Estimator → Waveform Synth   │  │
│  │  Soundboard playback engine (soundfile)               │  │
│  └───────────────────────────────────────────────────────┘  │
└──────────────────────────────┬──────────────────────────────┘
                               │ ctypes CDLL
                               ▼
┌─────────────────────────────────────────────────────────────┐
│          Native Windows 64-bit VST3 Dynamic Library         │
│          beatrice_2.0.0-rc.2.dll (x86_64-win)               │
│          + beatrice_paraphernalia_*/ model weights          │
└─────────────────────────────────────────────────────────────┘
```

---

## 📁 Project Structure

```
Beatrice-voicechanger-windows/
├── main.js                              # Electron main process & child process manager
├── renderer.js                          # Frontend UI logic, state, and API client
├── index.html                           # Window layout and controls
├── index.css                            # Styling system (6 themes × light/dark)
├── beatrice_audio.exe                   # Standalone packaged Windows audio backend
├── beatrice_audio.py                    # Python source audio backend + REST API
├── beatrice_loader.py                   # VST3 binary loader & ctypes bindings
├── package.json                         # Electron and build configurations
├── requirements.txt                     # Python dependencies
├── icon.png                             # App icon
├── assets/                              # Brand artwork & screenshots
├── build_dll/                           # Windows DLL definition and import libraries
├── beatrice_2.0.0-rc.2.vst3/
│   └── Contents/
│       └── x86_64-win/
│           ├── beatrice_2.0.0-rc.2.dll  # Native Windows 64-bit Beatrice DSP library
│           └── beatrice_2.0.0-rc.2.vst3 # VST3 plugin bundle
├── beatrice_paraphernalia_jvs/          # JVS Corpus (100 voices)
├── beatrice_paraphernalia_official_1/   # Official Model 1 (4 voices)
└── beatrice_paraphernalia_old_tts/      # Classic Old TTS (8 voices)
```

---

## ⚙️ Requirements

| Requirement | Specification |
|---|---|
| **Operating System** | Windows 10 or Windows 11 (64-bit) |
| **Processor** | 64-bit Intel / AMD CPU with AVX support |
| **Audio Routing** | [VB-Audio Cable](https://vb-audio.com/Cable/) or Voicemeeter |
| **RAM** | 4 GB+ recommended |
| **Node.js / Python** | Only required if developing or building from source |

> 🍎 **Need the Mac version?**
> Visit **[Beatrice-voicechanger-mac](https://github.com/satiricalguru/Beatrice-voicechanger-mac)** for the Apple Silicon (M1/M2/M3/M4) & Intel macOS release.

---

## 🔌 API Reference

The local audio backend exposes a REST API on `http://127.0.0.1:5005`:

| Endpoint | Method | Description |
|---|---|---|
| `/status` | GET | Current state: bypass, live dB meters, active device IDs, parameters |
| `/devices` | GET | Enumerate all available audio input and output devices |
| `/set_config?<param>=<value>` | GET | Adjust DSP parameters on-the-fly |
| `/set_model?model=<name>` | GET | Switch voice model set (`jvs`, `official_1`, `old_tts`, `custom:<name>`) |
| `/play_sound?file_path=<path>&hear_yourself=<bool>` | GET | Play soundboard audio track through virtual microphone |
| `/stop_sound` | GET | Stop active soundboard playback |

---

## 🌐 Official Links & Community

- 🌍 **Official Beatrice Website:** [project-beatrice-v2.github.io/Beatrice-website](https://project-beatrice-v2.github.io/Beatrice-website/)
- 🪟 **Windows Repository:** [satiricalguru/Beatrice-voicechanger-windows](https://github.com/satiricalguru/Beatrice-voicechanger-windows)
- 🍎 **macOS Repository:** [satiricalguru/Beatrice-voicechanger-mac](https://github.com/satiricalguru/Beatrice-voicechanger-mac)
- 🔬 **Upstream Beatrice DSP Engine:** [prj-beatrice/beatrice-vst](https://github.com/prj-beatrice/beatrice-vst)

---

## 🙏 Credits & Acknowledgements

- 🔬 **Beatrice DSP Engine** — [prj-beatrice/beatrice-vst](https://github.com/prj-beatrice/beatrice-vst)
- 🌐 **Project Beatrice Website** — [project-beatrice-v2.github.io/Beatrice-website](https://project-beatrice-v2.github.io/Beatrice-website/)
- 🎙️ **Voice Changer Concept** — [w-okada/voice-changer](https://github.com/w-okada/voice-changer)
- 🎌 **JVS Corpus** — [Shinnosuke Takamichi, UTokyo](https://sites.google.com/site/shinnosuketakamichi/research-topics/jvs_corpus) *(non-commercial use only)*
- 💻 **Maintained by** [Satirical Guru](https://github.com/satiricalguru)

---

## 📜 License

**MIT License** — Copyright © 2026 Jatin Pandey

The voice changer UI and Python wrapper are MIT-licensed. The Beatrice DSP engine is licensed under its original terms from [prj-beatrice](https://github.com/prj-beatrice/beatrice-vst).

> ⚠️ **JVS Corpus:** Voice model weights derived from the JVS Corpus are licensed for **non-commercial use only**. See `LICENSE` and `contributors.txt` for details.

---

<div align="center">

**Built with ❤️ for Windows using Electron · Python · Beatrice DSP · VB-Audio Cable**

⭐ **Star [Beatrice-voicechanger-windows](https://github.com/satiricalguru/Beatrice-voicechanger-windows) on GitHub!**

</div>
