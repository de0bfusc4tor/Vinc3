<p align="center"><img width="355" height="139" alt="VINC3_Banner" src="https://github.com/user-attachments/assets/73fdd804-39a1-4f99-a755-65c8733fd34f" /></p>

 _<p align="center">3D Spectral Analysis & DSP Metering Suite. Frequency visualization and precision audio monitoring._</p>

---

![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20Silicon%20%26%20Intel-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)</p>

---

<img width="1440" height="868" alt="VINC3 preview" src="https://github.com/user-attachments/assets/a0fbe069-f453-4489-9bcb-75d41733888b" />

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **3D Engine**: Three-dimensional audio spectrogram engine.
- **Metering Modules**: High Precision monitoring suite.
- **Standalone**: Runs as a native application on macOS (Sonoma, Sequoia, Tahoe) without a browser.
- **Zero Dependencies**: Fully offline capable. No internet connection required.
- **Minimalist UI**: Dark-themed, high-contrast interface optimized for low-light studio environments. 5 themes available.

---

## 𝐌𝐨𝐝𝐮𝐥𝐞𝐬
- **Spectrogram**: Three-dimensional view of your audio's spectral energy. Three Modes available. **Sphere** (radial energy core), **Wave** (terrain landscape), and **Cube** (geometric structure).

- **FFT Meter**: HD Fast Fourier Transform analyzer for surgical frequency monitoring. Incorporated Peak Tracking with automatic peak detection and labeling of the most prominent frequencies. Logarithmic Scaling with detailed response from 20Hz to 20kHz with high-DPI grid rendering.

- **Level Meters**: Industry-standard monitoring to ensure loudness compliance with real-time tracking of Momentary (M), Short-term (S), and Integrated (I) LUFS. Accurate dBFS monitoring with persistent "Max Peak" hold. Crest Factor trigger visualizes the peak-to-RMS ratio; indicators turn **Vibrant Red** when audio is heavily limited (< 6dB) or exceeding safety thresholds (-3dB).

- **Analog VU Meter**: Classic hardware inspired ballistic response for monitoring signal "weight". Ballistics design with standard 300ms integration time mimics physical studio gear. Hot Zone trigger with ticks and needles that turns red above 0dB to signal saturation levels.

- **Oscilloscope**: Real-time linear oscilloscope visualization with Left & Right for stereo image monitoring.

- **Stereo Monitor**: Stable _Zero-Crossing_ trigger. Phase and Width monitoring with phase correlation and the balance between Mid/Side information to ensure mono compatibility.

- **Linear Spectrogram**: A scrolling logarithmic history of frequency energy flowing from Left to Right. Monitors long-term resonances and spectral imbalances over a continuous timeline.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **DAWs**: Ableton 11+, Ableton 12+, Logic Pro & Reason.
- **Permissions**: Requires Microphone (for hardware input) and Screen Recording (for system audio loopback).

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

1. Download the latest [`VINC3.zip`](https://github.com/DeobfuscateMusic/VINC3/releases/tag/VINC3_1.0.0)
2. Extract & Drag `VINC3` to your `Applications` folder.
- _Note : Follow the macOS Permissions tutorial below for first-time setup, before use and before applying step 3._
3. Launch `VINC3`, `Allow` Microphone capture.
3. Select your audio source `MIC` or `SYSTEM`
4. Click on `INITIALIZE`. It will start the engine.

---

## 𝐦𝐚𝐜𝐎𝐒 𝐏𝐞𝐫𝐦𝐢𝐬𝐬𝐢𝐨𝐧𝐬

To function as a standalone analyzer. `VINC3` requires specific system access. Make sure to fill all these requirements before starting using :

### 𝟏. 𝐌𝐢𝐜𝐫𝐨𝐩𝐡𝐨𝐧𝐞 𝐀𝐜𝐜𝐞𝐬𝐬
Required to analyze audio from your interface or built-in mic.
- `System Settings` > `Privacy & Security` > `Microphone` > Add `VINC3`.

### 𝟐. 𝐒𝐜𝐫𝐞𝐞𝐧 𝐑𝐞𝐜𝐨𝐫𝐝𝐢𝐧𝐠
Required for **System Audio Loopback** (capturing audio from other softwares).
- `System Settings` > `Privacy & Security` > `Screen Recording` > Add `VINC3`.

- _Reminder: `VINC3` does not record a single pixel. It doesn't record audio. It doesn't record video. It doesn't require Internet. These permissions are macOS requirements for internal audio routing._

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬

- **MIC**: Audio source from your Microphone.
- **SYSTEM**: Audio source from your System.
- **INITIALIZE**: Initialize the engine with your selected audio source.
- **Resizable & mobile software**: Select the borders to resize or move `VINC3` window
- **Resizable & mobile modules**: Select the bottom right of the module to resize it. Hold `Left Click` to move the module.
- **Reset**: Revert the modules positions to default.
- **STOP**: Stop the engine.

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬

- **Sponsor / Benefactor**: Vincent P.

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><img width="91" height="78" alt="Logo_Deobfuscate_RoundXS" src="https://github.com/user-attachments/assets/9d6368ac-8089-4c9f-88c7-6ca648a56c7d" /></p>
<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>
