# iPhone 15 Pro Showcase

A responsive, Apple-inspired product landing page for the iPhone 15 Pro. The experience combines cinematic video, scroll-triggered storytelling, and an interactive 3D phone configurator to recreate a polished product-launch presentation.

> This is an independent front-end showcase project and is not affiliated with, endorsed by, or associated with Apple Inc.

## Highlights

- Responsive hero video with separate mobile and desktop media
- Animated highlights carousel with play, pause, and replay controls
- Interactive 3D iPhone model that can be rotated, resized, and recolored
- Scroll-triggered GSAP animations across the product-story sections
- Feature and A17 Pro gaming sections using bundled video and image assets
- Apple-inspired navigation and footer, styled with Tailwind CSS

## Built with

- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [GSAP](https://gsap.com/) and ScrollTrigger
- [Three.js](https://threejs.org/), React Three Fiber, and Drei

## Getting started

### Prerequisites

Install a current LTS version of [Node.js](https://nodejs.org/), which includes npm.

### Installation

```bash
git clone <your-repository-url>
cd AppleWebsite
npm install
```

### Development

```bash
npm run dev
```

Vite will print the local development URL in the terminal.

### Production build

```bash
npm run build
npm run preview
```

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Starts the Vite development server. |
| `npm run build` | Creates an optimized production build in `dist/`. |
| `npm run preview` | Serves the production build locally. |
| `npm run lint` | Runs ESLint across JavaScript and JSX files. |

## Project structure

```text
src/
  components/    Page sections, carousel, and 3D-model components
  constants/     Navigation, highlight, model, and footer data
  utils/         Static asset exports and GSAP helper functions
public/
  assets/        Images, SVGs, and videos used by the presentation
  models/        GLB model used by the interactive configurator
```

## Notes

The repository includes the media and 3D assets required to run the experience locally. The 3D model source attribution is retained in `src/components/IPhone.jsx`.
