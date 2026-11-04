<p align="center">
  <img src="./public/icon/shopping/buying.svg" alt="purple-cart" width="120" height="120">
</p>

<h1 align="center">🛒 purple-cart</h1>

<p align="center">
  "Just design cool stuff" - a Tailwind CSS playground for a checkout stepper UI<br>
  (setup → billing → order → done) with a set of hand-picked shopping icons.
</p>

<p align="center">
  <a href="#-whats-inside">✨ What's inside</a> •
  <a href="#-quick-start">🚀 Quick Start</a> •
  <a href="#-scripts">📦 Scripts</a> •
  <a href="#-structure">🏗️ Structure</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite" alt="Vite 8">
  <img src="https://img.shields.io/badge/Tailwind-3-06B6D4?logo=tailwindcss" alt="Tailwind CSS 3">
  <img src="https://img.shields.io/badge/PostCSS-8-DD3A0A?logo=postcss" alt="PostCSS">
  <img src="https://img.shields.io/badge/HTML-vanilla-E34F26?logo=html5" alt="HTML">
</p>

---

## ✨ What's inside

- **Checkout progress stepper** - four nodes joined by connector bars, labelled *setup*, *billing*, *order* and *done*, with a shopping-bag illustration at the end of the track
- **Dark-first palette** - `bg-stone-50 dark:bg-stone-950` page background with stone / slate accents
- **Shopping icon set** in `public/icon/shopping/` - cart, add to cart, clear cart, fast cart, cart with money, buy, buying, return purchase
- **Tailwind CSS 3** through PostCSS + Autoprefixer, with `style.css` providing the Vite starter base styles (Inter font stack, light/dark colour scheme)
- **Zero JavaScript** - a pure HTML + CSS design exploration served by Vite

## 🚀 Quick Start

Node 20.19+ / 22.12+ is required by Vite 8 (verified on Node 26).

```bash
npm install
npm run dev
```

Vite serves the page at `http://localhost:5173`.

## 📦 Scripts

| Script            | Description                              |
| ----------------- | ---------------------------------------- |
| `npm run dev`     | Vite development server with HMR         |
| `npm run build`   | Production build into `dist/`            |
| `npm run preview` | Preview the production build locally     |

## 🏗️ Structure

```
public/icon/shopping/     # SVG icons: cart, add_cart, clear_cart, Fast_Cart,
                          #   Cart_With_Money, buy, buying, return_purchase
index.html                # Stepper markup (Tailwind utility classes)
style.css                 # Tailwind directives + base styles
tailwind.config.js
postcss.config.js         # tailwindcss + autoprefixer
```

## 🚀 Deployment

`npm run build` outputs a static site to `dist/` that can be served from any static host.

## 📄 License

No license has been chosen yet.

## 👤 Author

**Jackson Makinda** - [makindajackson.com](https://makindajackson.com)

- 📧 Email: me@makindajackson.com
- 💼 LinkedIn: [Jackson Makinda](https://linkedin.com/in/makindajack)
- 🎨 Dribbble: [@makindajack](https://dribbble.com/makindajack)
- 🐦 Twitter: [@makindajack](https://twitter.com/makindajack)

---

Built with ❤️ in Dar es Salaam, Tanzania 🇹🇿
