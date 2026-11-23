# ACM Sathyabama Student Chapter

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Site-blue?style=for-the-badge&logo=github)](https://kumaranramesh2302.github.io/ACM_SATHYABAMA/)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)
[![ACM Chapter](https://img.shields.io/badge/ACM-Student%20Chapter-005b94?style=for-the-badge&logo=acm)](https://www.acm.org/)

The official website of the **ACM Student Chapter at Sathyabama Institute of Science and Technology**, Chennai, India. Engineered with cinematic web animations, dual light/dark themes, and interactive 3D particle stages.

---

### 🌐 Live Preview
Experience the live chapter website directly on GitHub Pages:  
👉 **[https://kumaranramesh2302.github.io/ACM_SATHYABAMA/](https://kumaranramesh2302.github.io/ACM_SATHYABAMA/)**

---

## ✨ Features & Architecture

### 1. Dual Adaptive Themes (Strict Contrast & Elegant Wave Styling)
- **Light Theme**: Clean arctic-white central content area with flowing blue-to-purple wave graphics along borders and cards, styled with high-contrast typography for legibility.
- **Dark Theme**: Deep space visual aesthetics featuring ambient cyan/violet glow, glowing borders, and dark glassmorphic cards.
- **Smooth Toggle**: Seamless theme transition with user preference stored in `localStorage`.

### 2. Cinematic Leadership Showcase (18 Members)
- **Dual-Player Video Cross-Fading**: Hardware-accelerated dual-video cross-fading for seamless transitions between office bearer profile reels without flickering.
- **120-Frame Canvas Scrubbing**: Smooth scroll-scrubbed interactive portraits synced to scroll progress.
- **Roster & Fast Navigation**: Interactive officer chip strip and auto-tour preview mode.
- **Complete Team**: Includes Chair (Kevin Samuel), Vice Chair, Secretary, Treasurer, Division Leads, and Media Team Leads (Rahul Rajan & ATHARSH).

### 3. Ambient 3D Particle Web Engine
- Custom HTML5 Canvas 2D engine rendering dynamic floating 3D nodes with perspective projection, gentle particle drift, and interactive cursor/touch attraction.

### 4. Interactive Divisions Hub (Five Teams. One Vision.)
- Deep-dive into chapter committees:
  - **Technical Team**: Core algorithms, hackathons, and systems engineering.
  - **Web Development**: Web apps, open source, and full-stack solutions.
  - **Design & Media**: Visual identity, cinematics, UI/UX, and creative brand design.
  - **Research & Innovation**: Technical publications, AI/ML, and emerging tech.
  - **Corporate Relations**: Sponsorships, industry networking, and event logistics.

### 5. Campus Heritage & Events Showcase
- Interactive modal popups displaying event photography, narrative recaps, and achievement milestones.

---

## 📁 Repository Structure

```text
ACM_SATHYABAMA/
├── index.html           # Core application (Markup, CSS variables, Animation engines)
├── README.md            # Chapter documentation & showcase
├── .nojekyll            # Ensures GitHub Pages serves all asset directories
├── .gitignore           # Clean exclusion rules for temporary files
└── public/
    ├── acm-logo.png     # Official ACM Chapter emblem
    ├── light_theme_waves.svg
    ├── campus/          # Campus photography
    ├── events/          # Event galleries & milestone highlights
    ├── models/          # 3D assets & medallions
    ├── team/            # Member portrait photography & cinematic reels
    ├── videos/          # Optimized chapter video assets
    └── frames/          # 120-frame canvas animation sequences
```

---

## 🚀 Running Locally

No build tools, bundlers, or package managers required. The application runs natively in any modern web browser:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kumaranramesh2302/ACM_SATHYABAMA.git
   cd ACM_SATHYABAMA
   ```

2. **Serve with any local static server:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Or Node.js
   npx serve .
   ```

3. **Open in your browser:**  
   Navigate to `http://localhost:8000`.

---

## 🏛️ Chapter Leadership & Affiliation

- **Institution**: Sathyabama Institute of Science and Technology, Chennai, India
- **Faculty Coordinator & Mentor**: Dr. K. Ashokkumar
- **Student Leadership**: Kevin Samuel (Chair) & Core Executive Team
- **Official Inquiries**: [acm@sathyabama.ac.in](mailto:acm@sathyabama.ac.in)

---

&copy; 2026 Sathyabama Institute ACM Student Chapter. All rights reserved.
