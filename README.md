<p align="center"><img width="355" height="139" alt="VINC3_Banner" src="https://github.com/user-attachments/assets/73fdd804-39a1-4f99-a755-65c8733fd34f" /></p>

 _<p align="center">Spectral Analysis & DSP Metering. Frequency Visualization & Precision Audio Monitoring._</p>

---

![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20Silicon%20%26%20Intel-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)</p>

---

https://github.com/user-attachments/assets/7ab03f56-2037-4e66-9a67-ac912e6d3599

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **3D Engine**: Three-dimensional audio spectrogram engine.
- **Metering Modules**: High Precision monitoring suite.
- **Standalone**: Runs as a native application on macOS (Sonoma, Sequoia, Tahoe) without a browser.
- **Zero Dependencies**: Fully offline capable. No internet connection required.
- **Minimalist UI**: Dark-themed, high-contrast interface optimized for low-light studio environments. 5 themes available.

---

## 𝐌𝐨𝐝𝐮𝐥𝐞𝐬
| Module | Description | Features |
| :--- | :--- | :--- |
| **Spectrogram** | 3D spectral energy visualization. | **Sphere**, **Wave**, **Cube** & **Terminal** modes. |
| **FFT Meter** | Surgical frequency monitoring via HD FFT. | Peak tracking, auto-labeling & Logarithmic scaling (20Hz-20kHz). |
| **Level Meters** | Industry-standard loudness compliance. | Real-time M/S/I LUFS, dBFS tracking & Crest Factor alerts. |
| **Analog VU** | Classic hardware-inspired ballistics. | 300ms integration time & Hot Zone saturation indicators. |
| **Oscilloscope** | Real-time linear waveform visualization. | Dual-channel (L/R) stereo image monitoring. |
| **Stereo Monitor** | Phase and width analysis. | Zero-crossing trigger, Phase Correlation & Mid/Side balance. |
| **Linear Spec** | Scrolling frequency energy history. | Logarithmic timeline for detecting long-term resonances. |

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **DAWs**: Ableton 11+, Ableton 12+, Logic Pro & Reason.
- **Permissions**: Requires Microphone (for hardware input) and Screen Recording (for system audio loopback).

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

1. Download the latest [`VINC3.zip`](https://github.com/DeobfuscateMusic/VINC3/releases/download/VINC3_1.0.0/VINC3.zip)
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

| Control | Description |
| :--- | :--- |
| **MIC** | Set audio source to your Microphone. |
| **SYSTEM** | Set audio source to your System audio. |
| **INITIALIZE** | Boot the engine using the selected audio source. |
| **STOP** | Terminate the engine and all active processing. |
| **RESET** | Revert all modules to their default factory positions. |
| **Software Scaling** | Select the window borders to resize or move the `VINC3` window. |
| **Module Scaling** | Drag the bottom-right corner to resize; hold `Left Click` to move. |

- _Note : To achieve the layout in the preview you will have to resize and move the modules windows. You can also create your own._

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬

- **Sponsor / Benefactor**: Vincent P.

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><img width="91" height="78" alt="Logo_Deobfuscate_RoundXS" src="https://github.com/user-attachments/assets/9d6368ac-8089-4c9f-88c7-6ca648a56c7d" /></p>
<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>
