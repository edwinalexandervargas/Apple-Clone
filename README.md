# Apple MacBook Pro Clone
 
A clone of Apple's MacBook Pro product page built with React, featuring 3D interactive models, scroll-driven animations, and video texture manipulation.
 
![Apple Clone](https://github.com/user-attachments/assets/1451d0d8-1ad3-4130-b1f1-791b71decd90)
![Apple Clone 2](https://github.com/user-attachments/assets/14099f38-9074-446c-81a4-b39fbe07204c)
🔗 [Live Demo](https://apple-clone-three-eta.vercel.app/)
 
> **Note:** This is a UI clone built for learning purposes. All product content and assets belong to Apple Inc.
 
## Features
 
- Hero section with cinematic auto-playing video at 2x playback speed
- Interactive 3D MacBook Pro viewer — rotate the model, switch between 14" and 16" sizes, and change the color
- GSAP scroll-driven animations throughout — pinned sections, fade-ins, and parallax effects
- Features section with a 3D MacBook that spins as you scroll, with video textures updating on the screen for each feature
- Performance section with animated floating product images
- Highlights masonry grid with staggered scroll animations
- Responsive design with mobile-specific layouts
## Tech Stack
 
- **React** — component-based UI library
- **Vite** — build tool and dev server
- **Tailwind CSS v4** — utility-first styling with custom design tokens
- **GSAP** — scroll-driven animations and timeline sequencing
- **React Three Fiber** — React renderer for Three.js
- **Three.js** — 3D rendering engine
- **@react-three/drei** — helper components for 3D scenes
- **gltfjsx** — converts GLB 3D model files into React components
- **Zustand** — global state management for model color, scale, and texture
- **react-responsive** — responsive breakpoint detection
## Getting Started
 
### Prerequisites
- Node.js installed on your machine
### Installation
 
1. Clone the repository
   ```bash
   git clone https://github.com/edwinalexandervargas/Apple-Clone.git
   cd Apple-Clone
   ```
 
2. Install dependencies
   ```bash
   npm install
   ```
 
3. Start the development server
   ```bash
   npm run dev
   ```
 
> **Note:** The project uses large 3D model files and video assets. Initial load time may be slow.
 
## What I Learned
 
- Rendering and manipulating interactive 3D models in the browser with React Three Fiber and Three.js
- Converting GLB 3D model files into React components using gltfjsx
- Applying video textures to 3D model surfaces with useVideoTexture
- Dynamically changing 3D model material colors while protecting specific meshes from color changes
- Building scroll-driven animations and pinned sections with GSAP ScrollTrigger
- Managing global 3D scene state with Zustand
- Implementing utility-first styling with Tailwind CSS v4 including custom design tokens and utilities
- Debugging 3D scene issues including duplicate renders, material conflicts, and mesh identification
- Resolving Git merge conflicts and managing detached HEAD states
