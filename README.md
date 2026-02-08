# MacBook GSAP Experience

A high-fidelity **Apple-style MacBook product experience** built with **React**, **GSAP**, **Three.js**, and **Tailwind CSS**.
This project focuses on **smooth animations**, **3D product interaction**, and **pixel-perfect UI**, inspired by Apple’s official product pages.



## ✨ Features

* 🎥 **GSAP-powered animations** (scroll-based & timeline-driven)
* 💻 **3D MacBook viewer** using `@react-three/fiber` & `three`
* 🎨 **Color & size switching** with real-time 3D updates
* ⚡ **Vite + React 19** for fast dev & builds
* 🧠 **Zustand state management**
* 📱 **Fully responsive layout**
* 🎯 **Tailwind CSS v4** with custom fonts & utilities
* 🖱️ Apple-like smooth scrolling & transitions



## 🧱 Tech Stack

### Core

* **React 19**
* **Vite**
* **Tailwind CSS 4**
* **GSAP & @gsap/react**

### 3D & Graphics

* **Three.js**
* **@react-three/fiber**
* **@react-three/drei**

### State & Utilities

* **Zustand**
* **clsx**
* **react-responsive**

All dependencies and scripts are defined in `package.json` 



## 📂 Project Structure

```bash
macbook-gsap/
├─ public/
│  ├─ fonts/
│  ├─ videos/
│  ├─ images/
│
├─ src/
│  ├─ components/
│  │  ├─ Navbar.jsx
│  │  ├─ Hero.jsx
│  │  ├─ ProductViewer.jsx
│  │
│  ├─ App.jsx
│  ├─ main.jsx
│  ├─ index.css
│
├─ index.html
├─ package.json
├─ package-lock.json
└─ README.md
```

Key entry points:

* `index.html` mounts the app 
* `main.jsx` bootstraps React
* `App.jsx` orchestrates sections & animations



## 🎬 Animations

### GSAP Usage

* Timeline-based transitions
* Scroll-triggered reveals
* Text, media & section entrance animations
* Hardware-accelerated transforms for smoothness

GSAP is integrated via `@gsap/react` for proper React lifecycle handling.



## 🧊 3D Product Viewer

The **MacBook 3D model** is rendered using:

* `@react-three/fiber` for React + Three.js binding
* `@react-three/drei` helpers
* Custom lighting & camera controls
* Zustand for color/size state syncing

The canvas is mounted inside the `#product-viewer` section and styled using Tailwind utilities.



## 🎨 Styling & Design System

### Tailwind CSS

* Tailwind v4 via Vite plugin
* Custom fonts loaded via `@font-face`
* Utility & component layers
* Apple-like typography & spacing

Defined in `index.css` 

### Design Tokens

```css
--color-primary: #0071e3;
--color-dark-100: #86868b;
--font-semibold: "SemiBold";
```



## 📱 Responsiveness

* Mobile-first layout
* Conditional animations for small screens
* Media-query-aware GSAP timelines
* `react-responsive` for breakpoint logic

Tested across:

* Mobile
* Tablet
* Laptop
* Ultra-wide screens



## 🧠 Inspiration

This project is inspired by:

* Apple MacBook product pages
* Modern WebGL storytelling
* High-end brand interaction design



## 📄 License

This project is for **educational & portfolio purposes**.

