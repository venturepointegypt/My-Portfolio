# Ismail Zidan — Senior IT Advisor Portfolio

A high-performance, cinematically-styled professional portfolio website designed for digital transformation leadership. Built with modern web technologies, custom GLSL shaders, and focused on visual storytelling and performance.

## 🚀 Key Features

### 1. High-Performance Particle Network
- **Custom Repulsion Logic**: Implemented a sophisticated force-based repulsion system that maintains a 60px minimum distance between nodes, preventing "clumping" and ensuring a polished, balanced constellation.
- **Delta-Capped Animation**: Real-time delta-time calculations with a 50ms cap to protect mobile CPU/battery usage while maintaining smooth 60fps on desktop.
- **Gesture-Based Interactivity**: Reacts to mouse *movement* rather than fixed position, creating a subtle parallax effect that feels responsive but never distracting.

### 2. Cinematic GLSL Gradient Architecture
- **Three.js Shader Integration**: Uses custom vertex and fragment shaders to render a procedural gradient mesh.
- **Unified Theme Switching**: Dark mode transitions are synchronized between CSS variables and GLSL uniforms via a JS bridging layer, ensuring the background and UI elements fade in perfect unison.

### 3. UX & Functional Enhancements
- **Custom Cursor System**: 1:1 hardware-accurate cursor with dynamic scaling micro-animations on interactive elements.
- **Interactive Navigation**: 
  - **Scroll Progress Bar**: A sleek indicator at the very top of the viewport tracking reading progress.
  - **Back-to-Top Button**: A floating high-impact CTA that appears after scrolling down, with smooth-scroll functionality.
  - **Active Nav Highlighting**: Uses `IntersectionObserver` to highlight the "current" section in the menu as you scroll.
- **3D Card Tilt**: Cards featuring specular glint effects that track cursor movement, adding tactile depth to expertise and project sections.

### 4. Technical Sophistication
- **SEO & Structured Data**: Built-in JSON-LD Person and WebSite schema for rich search result snippets and professional indexing.
- **FOUC Prevention**: Custom inline head-script to handle theme persistence (localStorage) before the first paint, preventing "flash of unstyled content."
- **Scroll-Triggered Visuals**:
  - **Timeline Path Drawing**: An animated SVG path that draws itself as you explore the professional experience history.
  - **Kinetic Text Reveal**: Staggered word-landing animations for the hero headlines.
  - **Animated Stats**: Smooth-easing counters for years of experience and government institutions.

## 🛠️ Tech Stack
- **Core**: HTML5, Vanilla CSS3, Modern JavaScript (ES6+)
- **Graphics**: [Three.js](https://threejs.org/) (WebGL), GLSL Shaders
- **Icons**: SVG (Lucide-inspired)
- **Forms**: [Web3Forms](https://web3forms.com/) (Serverless submission)
- **Fonts**: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (Serif), [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Sans-serif)

## 📂 Project Structure
- `index.html` — The core application containing UI, styles, and logic.
- `favicon.png` — Custom professional monogram.
- `Ismail_zidan_profile.jpg` — Profile asset utilized in Open Graph meta-tags.

## 🛡️ License
© 2026 Ismail Zidan. All rights reserved. Registered for professional consulting use across the MENA region.
