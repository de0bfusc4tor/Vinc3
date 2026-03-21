# 𝐕𝐢𝐧𝐜𝟑 - 𝐃𝐒𝐏 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬

> _3D Spectral Analysis & DSP Metering Suite. Designed for engineers, producers, and sound designers to provide immersive 3D frequency visualization and precision audio monitoring in a minimalist interface._

![Version](https://img.shields.io/badge/Version-0.9.9-green?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20Silicon%20%26%20Intel-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)

---

https://github.com/user-attachments/assets/8661320d-6327-4248-b481-d29fa9a212b6

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **3D Spectrogram Engine**: High-fidelity immersive visualization featuring three distinct modes: **Sphere** (radial), **Wave** (terrain), and **Cube** (geometric).
- **FFT Sniper**: High-precision Fast Fourier Transform analyzer with automatic peak detection and musical note identification (e.g., A4, C#2).
- **Precision Metering**: Industry-standard loudness monitoring including LUFS (Momentary, Short-term, Integrated), Peak & RMS (dBFS), and Max Peak Hold.
- **Analog VU Meter**: Classic hardware-inspired ballistic response with a 300ms integration time for monitoring signal "weight."
- **Oscilloscope**: Real-time time-domain visualization with a stable zero-crossing trigger for precise waveform inspection.
- **Spectral Heatmap (Sonogram)**: Scrolling logarithmic history of frequency energy to identify long-term resonances and spectral imbalances.
- 
---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **Permissions**: Requires Microphone (for hardware input) and Screen Recording (for system audio loopback).

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

### 𝐒𝐭𝐚𝐧𝐝𝐚𝐥𝐨𝐧𝐞
1. Download the latest [`VINC3.app.zip`](#).
2. Extract & Drag to your `Applications` folder.
3. **Note**: Follow the [macOS Permission Guide](#macos-permissions) below for first-time setup.

---

## 𝐦𝐚𝐜𝐎𝐒 𝐏𝐞𝐫𝐦𝐢𝐬𝐬𝐢𝐨𝐧𝐬

To function as a standalone analyzer, VINC3 requires specific system access:

### 𝟏. 𝐌𝐢𝐜𝐫𝐨𝐩𝐡𝐨𝐧𝐞 𝐀𝐜𝐜𝐞𝐬𝐬
Required to analyze audio from your interface or built-in mic.
- **System Settings** > **Privacy & Security** > **Microphone** > Enable **VINC3**.

### 𝟐. 𝐒𝐜𝐫𝐞𝐞𝐧 𝐑𝐞𝐜𝐨𝐫𝐝𝐢𝐧𝐠
Required for **System Audio Loopback** (capturing audio from other apps).
- **System Settings** > **Privacy & Security** > **Screen Recording** > Enable **VINC3**.
- _Note: VINC3 does not record pixels; this is a macOS requirement for internal audio routing._

---

## 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧 𝐌𝐨𝐝𝐞𝐬

**VINC3** provides three distinct ways to view the 3D spectral field:

- **Sphere**: A radial frequency distribution, ideal for identifying stereo width and energy clustering.
- **Wave**: A classic landscape view, perfect for watching transients and harmonic tails move through time.
- **Cube**: A structured, geometric approach for precise monitoring of frequency bands.

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬 & 𝐈𝐧𝐭𝐞𝐫𝐟𝐚𝐜𝐞

- **Logarithmic Grid**: Frequency response display from 20Hz to 20kHz.
- **Trigger**: Zero-crossing logic for the Oscilloscope to provide a static, readable waveform.
- **Hold**: Peak hold functionality to track maximum signal levels over time.

---

_This software and plugins are free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>

