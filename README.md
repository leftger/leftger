<img align="left" width="115" src="https://raw.githubusercontent.com/leftger/embedded-gui/master/assets/aztec_rustacean.png" alt="Aztec Ferris">

### Hey!

⚡ I'm **Gerzain**.

🦀 Embedded Systems Engineer (~10 yrs) bridging bare-metal **C** to pure **`no_std` Rust**.  
🛡️ Maintainer at [**@embassy-rs**](https://github.com/embassy-rs/embassy) (STM32 HAL/PAC, silicon bringup, and ported the **STM32WBA BLE stack**).  
🌵 Based in **Scottsdale, AZ** *(originally from Tomball, TX)*.

[![crates.io](https://img.shields.io/badge/crates.io-leftger-313131?style=flat&labelColor=545454&color=e05d44&logo=rust)](https://crates.io/users/leftger)
[![GitHub](https://img.shields.io/badge/GitHub-leftger-313131?style=flat&labelColor=545454&color=313131&logo=github)](https://github.com/leftger)
[![Embassy](https://img.shields.io/badge/Embassy-Maintainer-313131?style=flat&labelColor=545454&color=3b82f6)](https://github.com/embassy-rs/embassy)

<br>

---

#### 📦 Ecosystem & Open Source

I build foundational, zero-allocation (`no_std`) crates to bring desktop-grade graphics, DSP, audio, and machine learning to microcontrollers:

| Crate | Category | Description |
| :--- | :--- | :--- |
| [**`embedded-gui`**](https://github.com/leftger/embedded-gui) | 🎨 GUI & Animation | Zero-alloc HUD & UI toolkit, 2D flex/grid layouts, declarative KDL compiler, sub-ms dithered blits |
| [**`embedded-3dgfx`**](https://github.com/leftger/embedded-3dgfx) | 🧊 3D Engine | Fast software rasterizer, 3D pipelines, lighting models, and vector geometry for tiny displays |
| [**`embedded-dsp`**](https://github.com/leftger/embedded-dsp) | 📈 Signal Processing | Fixed/float DSP filters, FFT, IIR/FIR pipelines, and real-time audio/sensor math on bare metal |
| [**`embedded-audio`**](https://github.com/leftger/embedded-audio) | 🔊 Embedded Audio | PWM audio engine, wavetable/FM synthesis, effect banks, and multi-channel mixer for Cortex-M |
| [**`embedded-nn`**](https://github.com/leftger/embedded-nn) | 🧠 Edge AI / ML | Lightweight, allocator-free quantized neural network inference runtimes for microcontrollers |

<br>

#### ⚡ Core Focus & Hardware Bringup

* **Embassy & [`stm32-data`](https://github.com/embassy-rs/stm32-data):** Maintainer contributing across the [Embassy](https://github.com/embassy-rs/embassy) ecosystem:
  * **Silicon Bringup:** Register modeling and PAC generation for new STM32 families (**STM32N6**, **U5**, **H7R/S**, **C5**, **WBA**), including I3C, GFXMMU/GPU2D, and GTZC security subsystems.
  * **Wireless & HAL:** Ported and maintain the **STM32WBA BLE stack** and radio subsystems for Embassy.
  * **Core Drivers:** Async HAL features and driver reliability across `embassy-stm32` (ADC, I2C/DMA, RCC) and `embassy-time`.
* **Driver Architecture:** Big advocate of [@diondokter](https://github.com/diondokter)'s [`device-driver`](https://github.com/diondokter/device-driver) crate — declarative, bit-level type-safety is the gold standard for how peripheral drivers should be authored.
* **Solar & Telemetry:** Offline solar harvesting, MPPT telemetry, smart-home sensors, and low-power mesh radios.

<br>

#### 🎲 Trivia & Passions

* 🏛️ **Mesoamerican History:** Deeply fascinated by Mesoamerican history and Nahua civilization (which inspired the Aztec Ferris above!). I own a full 12-volume complete set of the *Florentine Codex* (Dibble & Anderson English/Nahuatl translation).
* 📐 **Dinner with a Legend:** I once had dinner with **Prof. Gilbert Strang** (MIT Linear Algebra legend). Naturally, it fueled a lifetime passion for matrix kernels and DSP transforms on microcontrollers.
* ☕ ~10 years in bare-metal C, now proving that safe, async Rust can match or beat hand-tuned C on microcontrollers.

---

<div align="center">
  <sub>Built with ⚡ and bare-metal Rust.</sub>
</div>
