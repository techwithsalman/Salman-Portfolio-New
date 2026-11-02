# Tech With Salman — Personal Portfolio

An interactive, high-performance personal portfolio website for **Salman Khan** (Tech With Salman) — UI/UX Designer, Full Stack Developer & AI Automation Builder based in Karachi, Pakistan.

---

## 🌟 Overview

This portfolio showcases creative development, interactive experiences, and digital engineering. It combines physics simulations, liquid canvas shaders, and dynamic 3D-styled interactive elements to present multidisciplinary capabilities in design, web development, SaaS, and AI automation.

- **Portfolio Owner:** Salman Khan ([Tech With Salman](https://techwithsalman.netlify.app/))
- **Email:** [hello@salman.design](mailto:hello@salman.design)
- **WhatsApp:** [+92 315 2181308](https://wa.me/923152181308)

---

## 🚀 Key Features

1. **Interactive Discipline Doors**
   - Five interactive 3D-perspective doors representing key services:
     1. **Web Development**
     2. **Software & SaaS**
     3. **UI/UX Design**
     4. **Graphic Design**
     5. **AI & Automation**
   - Features real-time perspective tilt, door opening physics, contextual detail panels, and custom walkthrough page transitions.

2. **Verlet Physics Theme Pull-Cord**
   - Interactive pull-rope simulated using Verlet numerical integration (particles, distance constraints, gravity, damping, and mouse/touch drag).
   - Toggles smoothly between **Dark Mode** and **Warm Light Mode** upon reaching release tension.

3. **Liquid Reveal Hero Portrait**
   - Custom canvas shader providing a fluid grayscale-to-color reveal on hover across the transparent hero portrait.

4. **Animated Flip Notebook**
   - Realistic ring-bound flip calendar notebook cycling through professional specializations.

5. **"My Story" Career Timeline Wheel**
   - Interactive rotary timeline showcasing career milestones, design agency experience, SaaS launches, and development projects.

6. **Interactive Contact Modal**
   - Quick-access overlay for project inquiries, direct email, and WhatsApp connectivity.

---

## 🎨 Dual Theme System (Light & Dark)

The website features a semantic CSS custom property system supporting both Dark and Warm Light palettes with WCAG AA compliance across all components:

### Dark Theme (`html[data-mode="dark"]`)
- **Hero & Page Background:** `#100B16` / `#080509` with deep violet gradients
- **Surfaces & Cards:** `#160B24` / `#1C0F2B`
- **Primary Text:** `#F7F3FA` (Crisp, high contrast)
- **Secondary Text:** `#B8ADBF`
- **Accent:** `#852DFF` (Vibrant electric purple)
- **Borders:** Subtle muted violet (`rgba(133, 45, 255, 0.2)`)

### Light Theme (`html[data-mode="light"]`)
- **Hero & Page Background:** `#F5F1EF` with warm off-white gradient
- **Surfaces & Cards:** `#FFFFFF` / `#EFE9E4`
- **Primary Text:** `#18141A` (Deep charcoal, high readability)
- **Secondary Text:** `#605965`
- **Accent:** `#852DFF`
- **Borders:** Subtle warm stone gray (`rgba(96, 89, 101, 0.18)`)

Theme state is synchronized with `localStorage` (`theme-mode`), dynamic `meta[name="theme-color"]`, and accessible programmatically via `window.setMode('dark' | 'light')` and `window.toggleMode()`.

---

## 🛠️ Tech Stack

- **Core:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Graphics & Shaders:** HTML5 Canvas, WebGL shader liquid effects
- **Physics Engine:** Verlet integration particle rope model
- **Typography:** Self-hosted Onest variable font (`woff2`)
- **Styling:** CSS variables, backdrop filters, CSS Grid, Flexbox, hardware-accelerated transforms
- **Zero Heavy Frameworks:** Pure web performance with instant page loads and zero bundle overhead

---

## 💻 Local Setup & Development

### Prerequisites
- [Node.js](https://nodejs.org/) (version 16 or newer recommended)

### Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/techwithsalman/Salman-Portfolio-New.git
   cd Salman-Portfolio-New
   ```

2. Start the local server:
   ```bash
   node server.js
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000/
   ```

### Alternative Static Servers
You can also preview using any standard static file server:
```bash
# Using Python
python -m http.server 3000

# Using npx serve
npx serve .
```

---

## 📁 Project Structure

```
├── index.html              # Main homepage & core interactive application
├── server.js               # Zero-dependency local Node.js static server with SPA fallback
├── README.md               # Documentation
├── .gitignore              # Ignored files and directories
├── salman.png              # Hero section high-resolution portrait
├── Salman_CV.pdf           # Downloadable curriculum vitae
├── 404.html                # Custom 404 error page
├── assets/                 # SVGs, sound effects, animations, door textures
├── fonts/                  # Self-hosted web fonts (Onest)
├── vendor/                 # Supporting libraries (canvas utilities)
├── web-developer/          # Subpage: Web Development door walkthrough
├── app-developer/          # Subpage: Software & SaaS door walkthrough
├── ui-ux-designer/         # Subpage: UI/UX Design door walkthrough
├── graphic-designer/       # Subpage: Graphic Design door walkthrough
├── photographer/           # Subpage: AI & Automation door walkthrough
└── legal/                  # Privacy policy and legal notices
```

---

## 📜 Credits & Attribution

- **Original Creative Direction & Architecture:** Inspired by [Rishi Thakor](https://therishithakor.com/)
- **Customized, Re-engineered & Expanded:** Salman Khan ([Tech With Salman](https://techwithsalman.netlify.app/))
