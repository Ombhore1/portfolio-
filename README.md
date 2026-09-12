# Hero Section Demo

A ready-to-run Vite + React + Tailwind + Framer Motion project.

## Why the .jsx file didn't work as a .html file

Browsers can't run JSX or React on their own — there's no build step in a
plain HTML file. This project adds that build step (Vite) so the component
actually compiles and renders.

## How to run it

You need [Node.js](https://nodejs.org) installed (v18+). Then, in this
folder:

```bash
npm install
npm run dev
```

Vite will print a local URL (usually `http://localhost:5173`) — open that in
your browser to see the hero section. Edit `src/HeroSection.jsx` and the page
will hot-reload automatically.

## Project structure

```
index.html              <- HTML shell, loads src/main.jsx
src/main.jsx             <- mounts <HeroSection /> into #root
src/HeroSection.jsx       <- the component itself (edit this)
src/index.css             <- Tailwind + Inter font + blink keyframe
tailwind.config.js         <- Tailwind setup, points sans font at Inter
postcss.config.js
vite.config.js
package.json
```
