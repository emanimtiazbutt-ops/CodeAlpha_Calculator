# Chic Studio Dashboard Calculator (CodeAlpha Internship Task 2)

An advanced, production-grade web calculator featuring a premium **"Chic Cyber-Pastel"** workspace aesthetic. This application moves away from standard layouts to deliver an immersive, dual-mode engineering engine built using semantic HTML5, glassmorphic CSS styling rules, and native Vanilla JavaScript (ES6+).

---

##  Key Features

- **Dual-Mode Computation Deck:** A responsive toggle switch that smoothly expands the workspace from a standard arithmetic interface into an extended engineering/scientific panel ($\sin, \cos, \tan, \log, \ln$, square roots, squares, and constants).
- **Persistent Memory Ledger:** A real-time audit ledger panel that dynamically records, logs, and displays previous equations and computations in a scrollable history stack.
- **Synthesized Micro-Haptics:** Utilizes native Web Audio API nodes (`AudioContext`) to synthesize high-fidelity chime confirmations directly on button clicks without downloading or relying on heavy external audio assets.
- **Full Hardware Keyboard Support:** Integrated global DOM event listeners tracking system keydown matrices. Type numerical tokens, use `Backspace` to delete specific entries, `Enter` to execute, and `Escape` to clear.
- **Robust Math Precision:** Calculations are run inside a sanitizing precision wrapper that elegantly handles JavaScript floating-point binary issues, ensuring calculations like `0.1 + 0.2` return exactly `0.3` instead of long fractional anomalies.

---

##  Technical Breakdown

### Frontend Architecture
- **Structure:** Semantic HTML5
- **Layout & Aesthetics:** CSS3 Grid and Flexbox layouts configured with modern backdrop-blur glassmorphic filters (`backdrop-filter`), smooth hardware-accelerated transforms, and a custom matte pastel pink palette.

### Core Calculation Engine
- **State Engine:** Pure Vanilla JavaScript (ES6+)
- **Parser Routing:** Secure text tokenization pipelines utilizing strict mathematical execution contexts (`"use strict";`) combined with automated parenthetical closure safeguards to prevent visual layout collapses on syntax exceptions.

---

## 📂 Project Directory Structure

```text
CodeAlpha_Calculator/
│
├── index.html        # Unified core markup, styling configurations, and script engine
└── README.md         # Production documentation sheet
