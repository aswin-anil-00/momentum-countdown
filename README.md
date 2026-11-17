# MOMENTUM — Make Every Moment Count

> *Time is limited. Progress is intentional. Every day matters.*

**MOMENTUM** is a luxury minimalist personal countdown and milestone timepiece inspired by Swiss horology, Apple’s interface clarity, and editorial print layouts. Designed as a calm, distraction-free lock-screen experience, it connects long-term goals with daily intentional action.

![Project Cover](./cover.jpg)

---

## ✨ Key Features

- **Lock-Screen Hero & Presentation Mode**: Real-time tabular countdown (`DAYS : HOURS : MINUTES : SECONDS`) calculated strictly from local target timestamps, complete with a full-screen distraction-free **Lock View** and live seconds sweep ring.
- **Dual Luxury Surfaces**: Seamlessly switch between **Ivory Daylight** (`#F7F5F0` warm ivory, `#B89B68` champagne gold) and **Nocturne** (`#111111` obsidian, `#C5A878` gold).
- **Separated Horological Progress**: Independently tracks **Time Elapsed** (via a radial chronometer arc and dual-scale vernier bar with 10% and 2% watchmaker ticks) and **Milestone Completion** (via a segmented chapter bar).
- **Interactive Milestone Journey**: Spotlight card for **Your Next Milestone**, relative day badges, tactile SVG stroke-draw completion animations, and full add/edit/delete capabilities.
- **Today Matters (Daily Focus)**: Single-intention daily tracker with click-to-edit tasks, automatic midnight rollover, and cumulative days-logged tracking.
- **Chapter Presets & Persistence**: Built-in goal templates (*Creative Launch*, *Endurance Arc*, *Mastery Study*) and automatic `localStorage` persistence with zero backend dependencies.

---

## 🛠️ Tech Stack

- **HTML5** (Semantic structure & accessible ARIA controls)
- **Tailwind CSS** (via CDN for zero-build deployment)
- **Vanilla JavaScript (ES6+)** (Timestamp-accurate chronometer engine & state persistence)
- **Typography**: `Cormorant Garamond` (editorial serif) & `Plus Jakarta Sans` (clean geometric sans-serif)

---

## 🚀 Getting Started

Because MOMENTUM is engineered as a self-contained, zero-dependency single-page application, no build step or package installation is required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/momentum.git
   cd momentum
