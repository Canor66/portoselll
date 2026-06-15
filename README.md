# Glass Porto

A modern portfolio landing page with an interactive 3D glass shard experience built using React, Vite, Tailwind CSS, and Three.js.

## Project Overview

This project showcases:
- Reactive 3D presentation using `@react-three/fiber` and `@react-three/drei`
- Custom glass shard interface and animated interaction
- Responsive overlay panels for content, gallery, experience, services, and contact
- Production-ready build and optimization via Vite

## Tech Stack

- React 19
- Vite
- Tailwind CSS
- Three.js
- React Three Fiber
- React Three Drei
- Lucide React icons

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open `http://localhost:5173` in your browser.

## Production Build

Build the optimized production bundle:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Repository Guidance

This repository should include source code and configuration files only. Recommended tracked folders:

- `src/`
- `public/`
- `package.json`
- `package-lock.json`
- `vite.config.js`
- `eslint.config.js`
- `README.md`
- `.gitignore`

Do not commit generated or dependency folders:

- `node_modules/`
- `dist/`
- log files

## Notes

- The project is designed to look polished in modern browsers.
- Three.js adds significant bundle size, so build performance should be monitored.
- For better deployment, use a static host like Vercel or Netlify.
