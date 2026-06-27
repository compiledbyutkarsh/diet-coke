<div align="center">

# 🥤 Diet Coke — Interactive 3D Landing Page

**A scroll-driven 3D product experience built with React Three Fiber.**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

*A cinematic, scroll-driven 3D product showcase — no templates, no shortcuts.*

</div>

---

## What is this?

A premium interactive landing page for Diet Coke featuring a fully animated 3D can that responds to scroll position in real time. Built with React Three Fiber and custom scroll mechanics — no scroll libraries, no animation frameworks.

The 3D can floats, rotates, and glides across the screen as the user scrolls through three cinematic sections — each with its own layout, typography, and atmosphere.

---

## Features

| Feature | Details |
|---------|---------|
| 3D Model Rendering | GLTF model loaded via `@react-three/drei`, rendered with ACESFilmic tone mapping |
| Scroll-driven Animation | Custom scroll ref + eased interpolation — no GSAP, no ScrollTrigger |
| Camera Rig | Dynamic camera position and lookAt target shift per scroll section |
| Float Animation | Sine-wave floating idle animation on the can |
| Slide-up Entrance | Can slides in from below after hero text animates in (2.4s delay) |
| Contact Shadows | Soft red-tinted shadows beneath the can |
| Noise + Vignette | CSS layered grain and vignette for cinematic feel |
| Error Boundary | React class component catches 3D model failures gracefully |

---

## Scroll Sections

**01 — Hero**: Full-screen intro with animated title, eyebrow text, and scroll hint.

**02 — Bold Flavor**: Can shifts right. Stats row shows 0 calories, 0g sugar, 40+ years icon.

**03 — Made for the Daring**: Can glides left. Flavor variants listed — Classic, Mango, Cherry, Lime.

---

## Tech Stack

- **React 18** — component architecture
- **Vite** — dev server and bundler
- **React Three Fiber** — declarative Three.js in React
- **@react-three/drei** — GLTF loader, Environment, ContactShadows
- **Three.js** — 3D math, lerp, easing, tone mapping
- **CSS** — noise overlay, vignette, scroll animations, section layouts

---

## Run Locally

```bash
git clone https://github.com/compiledbyutkarsh/diet-coke.git
cd diet-coke/vite-project
npm install
npm run dev
```

---

<div align="center">
<sub>Built with React Three Fiber — no animation libraries, no shortcuts.</sub>
</div>
