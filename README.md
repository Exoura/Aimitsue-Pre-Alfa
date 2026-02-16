# Aimitsue Pre-Alfa v0.1 - High-Precision Input Emulator

> **Experience Console-Like Smoothness with Mouse Precision.**  
> Aimitsue translates raw mouse input into high-fidelity virtual controller output, featuring a "Humanized Physics Engine" that eliminates the robotic feel of traditional remappers.



## 🚀 Key Features

### 🎮 Humanized Physics Engine
Unlike standard remappers that simply map mouse delta to stick deflection, Aimitsue simulates the physical properties of a real analog stick:
*   **Velocity Mirroring**: Uses advanced fluid dynamics to convert mouse speed into realistic stick tilt.
*   **Zero-Latency Braking**: A 25Hz virtual spring ensures the stick snaps back instantly when you stop moving, preventing "drift" or floaty aim.
*   **Surgical 1:1 Parity**: A dedicated zero-smoothing stage for micro-movements, ensuring pixel-perfect accuracy for sniping.
*   **Anti-Jitter Filtering**: Intelligent noise suppression removes hand tremors without adding input lag.

### 🌌 Cinematic Visual Experience
A fully immersive UI built with modern graphical standards:
*   **Ultra Rain System**: Optimized, multi-layered parallax rain simulation with refraction and splash effects.
*   **Neon Glassmorphism**: Translucent, frosted-glass UI elements with dynamic lighting.
*   **Reactive Background**: The environment reacts to your mouse movements in real-time.

### ⚔️ Driver-Level Integration
*   **Interception Driver**: Captures raw mouse input at the kernel level for lowest possible latency (bypassing Windows pointer ballistics).
*   **ViGEmBus Integration**: Emulates a native Xbox 360 controller, ensuring 100% compatibility with all games (COD, Apex, Halo, etc.).

---

## 🛠️ Prerequisites

Before running Aimitsue, ensure you have the following installed:

1.  **[Interception Driver](https://github.com/oblitum/Interception/releases)** (Required for Input)
    *   *Note: Run `install-interception.exe /install` as Administrator.*
           or
          *watch this* https://www.youtube.com/watch?v=IRDSTomCGBs
2.  **[ViGEmBus Driver](https://github.com/ViGEm/ViGEmBus/releases)** (Required for Output also) 

they have build in Installer you don't need to Install it manualy


3.  **[Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist)** (x64)

---

## 📦 Installation & Usage

1.  **Download** the latest release.
2.  **Extract** the zip file to a folder of your choice.
3.  **Run `Aimitsue.exe`** as Administrator.
4.  **Configure**:
    *   Adjust **Sensitivity** to your preference.
    *   Tweak **Smoothness** (lower = snappier, higher = fluid).
    *   Set **Deadzone** to match your game's settings.
5.  **Activate**: Press `F6` (default) or click the Toggle button to start emulation.
    *   *Press `F6` to release the mouse cursor.*

---

## ⚙️ Advanced Settings

*   **Curve Response**: Linear, Aggressive, or Relaxed curves to fine-tune aim acceleration.
*   **Y-Ratio**: Adjust vertical sensitivity independently (useful for recoil control).
*   **Bleed-Through**: Allow native mouse input to pass through (hybrid play).

---

---

## ⚖️ Disclaimer

This software is intended for accessibility and personal customization purposes. Aimitsue is a tool for translating input, not a cheat.
*   **Interception Driver**: ⚠️ **WARNING: RISKY.** This driver is **DETECTED** by many competitive FPS games (e.g., Vanguard, FaceIT). Using it may result in bans or kicks.
*   **ViGEmBus**: The industry standard for virtual gamepad emulation.

> **Note:** Use at your own risk. Im not responsible for any bans or account actions.

---

*(c) 2026 Aimitsue Exoura . Built with ImGui & DX11.*
