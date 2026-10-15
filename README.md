# ⚡ Adaptive Accessibility Studio (WCAG 2.1 AA & AAA)

[![WCAG 2.1](https://img.shields.io/badge/WCAG%202.1-Level%20AA%20%26%20AAA-00e5ff?style=for-the-badge&logo=w3c&logoColor=white)](https://www.w3.org/WAI/standards-guidelines/wcag/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Synthesized%20FX-ff2a85?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero%20(Pure%20Vanilla)-00f098?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-ffd600?style=for-the-badge)](LICENSE)

> **Adaptive Accessibility Tool** is a high-energy, interactive, and beautifully animated accessibility engineering workbench and WCAG 2.1 / APCA playground. It combines real-time color perception math, an interactive gamified remediation arena, simulated screen reader voice synthesis, live code static linting, and formal audit reporting into a single zero-dependency web application.

---

## 🌟 Key Features Overview

### 🎹 1. Keyboard Patterns & ARIA Architecture
- **Full Keyboard Operability**: Test complex interactive widgets without touching a mouse.
- **Roving Tabindex Tablist**: W3C APG-compliant tab navigation with `<kbd>ArrowLeft</kbd>`, `<kbd>ArrowRight</kbd>`, `<kbd>Home</kbd>`, and `<kbd>End</kbd>`.
- **Accessible Accordions**: Semantic regions controlled by `aria-expanded` and `aria-controls` with smooth chevron animations.
- **Native `<dialog>` Focus Trap**: Modal dialog that traps Tab focus, responds to `<kbd>Esc</kbd>`, and restores focus upon dismissal.
- **Accessible Action Menu**: Dropdown with roving keyboard focus and keyboard dismissal.
- **Custom ARIA Slider**: Built with `role="slider"`, `aria-valuenow`, `aria-valuemin`, `aria-valuemax`, and `aria-valuetext` supporting arrow keys and page stepping.
- **Accessible Switch**: Custom toggle control utilizing `role="switch"` and `aria-checked`.
- **Form Validation & Error Summary**: Submitting invalid data generates an interactive Error Summary box that captures focus and links directly to offending fields via `aria-describedby` and `aria-invalid`.
- **Live Focus & Keypress Inspector**: Real-time HUD logging active elements, roles, and keystroke events.

---

### 🌈 2. Color Contrast Engine, APCA & Vision Simulator
- **Dual Algorithm Scoring**:
  - **WCAG 2.1 Relative Luminance Ratio**: Exact mathematical calculation against AA (4.5:1 / 3:1) and AAA (7:1 / 4.5:1) thresholds.
  - **APCA (Accessible Perceptual Contrast Algorithm)**: Preview candidate algorithm for WCAG 3.0 measuring lightness contrast ($L^c$).
- **One-Click Color Actions**:
  - **Swap Colors**: Instantly flip foreground and background values.
  - **Auto-Suggest Passing Color**: Calculates and applies the closest high-contrast passing tone while maintaining hue.
  - **Preset Accessible Palettes**: Curated accessible color sets including *Electric Deep Space*, *Cyber Mint*, *Solar Flare*, and *Neon Velvet*.
- **Color Vision Deficiency Simulators**: Real-time SVG matrix filters:
  - **Protanopia** (Red-blind)
  - **Deuteranopia** (Green-blind)
  - **Tritanopia** (Blue-blind)
  - **Achromatopsia** (Complete monochromacy)
  - **Cataracts / Cloudiness**
  - **Low Vision / Blur**
- **Reflow & Text Spacing Testbench**:
  - **Force 320px Viewport (SC 1.4.10)**: Validates horizontal scroll prevention at 400% zoom.
  - **Custom Text Spacing (SC 1.4.12)**: Verifies legibility with enlarged line, paragraph, and letter spacing.

---

### 🕹️ 3. Gamified Remediation Arena ("Brew & Bean")
- **Interactive Bug Hunter Game**: An authentic e-commerce store with **14 deliberate accessibility barriers**.
- **Live XP & Rank Tracker**: Earn XP and advance from *A11y Novice* to *Accessibility Grandmaster*.
- **Granular 1-Click Fixes**: Patch individual barriers in the live DOM and inspect side-by-side code diffs (`Before` vs `After`).
- **Auto-Fix All & Reset**: Transform the broken UI into an accessible storefront with confetti celebration, or reset to broken state for demonstration.
- **Side-by-Side Mode**: Compare the non-conforming and conforming interfaces simultaneously.

---

### 🔬 4. Live In-Browser A11y Code Linter & Focus Styler
- **Real-Time Static Heuristics**: Paste or write custom HTML markup to instantly scan for:
  - Missing `alt` attributes on `<img>` tags (SC 1.1.1)
  - Unnamed or icon-only buttons (SC 4.1.2)
  - Input controls missing associated `<label>` or ARIA names (SC 3.3.2)
  - Positive `tabindex` anti-patterns altering natural DOM order (SC 2.4.3)
  - Clickable non-interactive `<div>` elements without keyboard handlers (SC 2.1.1)
- **Focus Ring Customizer Studio**: Interactively configure focus indicator thickness, offset, and color to verify SC 2.4.7 and SC 2.4.11 / 2.4.13 compliance.

---

### 📋 5. Professional WCAG 2.1 AA / AAA Audit & Report Generator
- **Comprehensive POUR Checklist**: 18 foundational Success Criteria covering:
  - **Perceivable**: Text alternatives, info & relationships, color usage, contrast, reflow, non-text contrast, text spacing.
  - **Operable**: Keyboard operability, no keyboard traps, bypass blocks (skip links), focus order, link purpose, focus visible.
  - **Understandable**: Language of page, error identification, labels & instructions.
  - **Robust**: Name/role/value, status messages (`role="status"` / `aria-live`).
- **Export & Delivery Options**:
  - Generate formal audit document with pass rate percentages and failure summaries.
  - One-click **Copy to Clipboard**.
  - One-click **Print / Save to PDF** with dedicated clean print stylesheet.

---

### 🔊 6. Synthesized Web Audio & Screen Reader Simulator (TTS)
- **Web Audio Sound Effects**: Synthesizes pleasant harmonic feedback for tab transitions, tactile button clicks, modal open/close sweeps, accordion toggles, and celebratory arpeggios.
- **Simulated Screen Reader Engine**: Integrated with `window.speechSynthesis` and an animated sound equalizer HUD. Users can experience how assistive technologies speak element roles, names, and dynamic states without needing external screen reader software installed.

---

## 🎨 Themes Included

| Theme Name | Description |
| :--- | :--- |
| **Electric Funk** *(Default)* | Vibrant ultraviolet canvas with glowing magenta, electric cyan, and neon amber accents. |
| **Retro Synth** | 80s synthwave sunset palette with deep purple and glowing turquoise. |
| **Cyber Dark** | Modern obsidian slate with luminescent mint green and sapphire accents. |
| **Fresh Day** | High-contrast, clean daygroove mode with saturated purple and rose highlights. |
| **High Contrast** | Pitch black (`#000`) with canary yellow (`#ffee00`) and neon green (`#00ff7f`) exceeding WCAG AAA standards. |

---

## 🚀 Quick Start / Local Setup

No build tools, bundlers, or package managers required. Simply clone and open:

```bash
# Clone the repository
git clone https://github.com/zarrar24/Adaptive-Accessibility-Tool.git

# Navigate into the project folder
cd Adaptive-Accessibility-Tool

# Open in your browser (Windows)
start index.html

# Open in your browser (macOS)
open index.html

# Open in your browser (Linux)
xdg-open index.html
```

---

## 🌐 Deploy to GitHub Pages

To host this tool as a free live web app:

1. Go to your GitHub repository: `https://github.com/zarrar24/Adaptive-Accessibility-Tool`
2. Navigate to **Settings** &rarr; **Pages** (under Code and automation).
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Within a few moments, your app will be live at:
   `https://zarrar24.github.io/Adaptive-Accessibility-Tool/`

---

## 📁 Repository Structure

```
Adaptive-Accessibility-Tool/
├── index.html                       # Primary GitHub Pages web app entrypoint
├── WCAG-Accessibility-Studio.html   # Standalone production distribution file
├── README.md                        # Comprehensive documentation & guide
├── LICENSE                          # MIT Open Source License
└── .gitignore                       # Standard git ignore definitions
```

---

## 🛡️ WCAG 2.1 Conformance Matrix

| Criterion | Level | Description | How this Tool Tests / Implements |
| :--- | :---: | :--- | :--- |
| **1.1.1** | A | Non-text Content | Linter scans for missing `alt`; Bug Hunt demonstrates decorative vs informative image markup. |
| **1.3.1** | A | Info and Relationships | Validates sequential headings (`h1`&rarr;`h2`), semantic tables with `th` scope, and form associations. |
| **1.4.1** | A | Use of Color | Error states demonstrate text labels and icons rather than border color alone. |
| **1.4.3** | AA | Contrast (Minimum) | Relative luminance calculator measures exact ratios against 4.5:1 and 3:1 requirements. |
| **1.4.10** | AA | Reflow | Viewport reflow simulation tests content down to 320px width without horizontal scrollbars. |
| **1.4.11** | AA | Non-text Contrast | Tests focus indicators and UI control borders against 3:1 contrast targets. |
| **1.4.12** | AA | Text Spacing | Tests custom letter spacing (0.12em), word spacing (0.16em), and line height (1.5+). |
| **2.1.1** | A | Keyboard | All custom components (tabs, accordions, modals, menus, sliders) operable via standard keys. |
| **2.1.2** | A | No Keyboard Trap | Modal dialog provides `<kbd>Esc</kbd>` exit and restores focus; demonstrates trap avoidance. |
| **2.4.1** | A | Bypass Blocks | Skip to main content link styled with animated keyboard access (`#main`). |
| **2.4.3** | A | Focus Order | Real-time keystroke inspector catches positive `tabindex` anti-patterns. |
| **2.4.4** | A | Link Purpose | Demonstrates meaningful link copy over vague phrases like "click here". |
| **2.4.7** | AA | Focus Visible | Focus ring styler guarantees visible, high-contrast outlines for all interactive elements. |
| **3.3.1** | A | Error Identification | Validated form highlights errors in text with clear remediation guidance. |
| **3.3.2** | A | Labels or Instructions | Explicit `<label for="...">` associations tested across all inputs. |
| **4.1.2** | A | Name, Role, Value | Screen reader simulator announces roles and states (`aria-expanded`, `aria-checked`, `aria-valuenow`). |
| **4.1.3** | AA | Status Messages | Dynamic cart updates and form alerts announced via `role="status"` and `aria-live="polite"`. |

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full details.

---

Made with ❤️ for inclusive, barrier-free web experiences.
