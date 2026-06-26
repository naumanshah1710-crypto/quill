# Quill — AI Writing Workspace Landing Page

A modern, responsive landing page for **Quill**, an AI writing workspace. Built with React, Vite, Tailwind CSS, and Framer Motion. Dark-themed with purple accent, smooth scroll animations, and a fully interactive hero demo.

> **Made with the collaboration of [haideralio73](https://github.com/haideralio73) and [naumanshah1710-crypto](https://github.com/naumanshah1710-crypto)**

---

# live At: https://quillv1.netlify.app

## Features

- Typewriter animation in the hero section
- Live streaming text demo with copy-to-clipboard
- Tone selector (Professional / Casual / Persuasive)
- Animated logo marquee strip
- 6 feature cards with icons
- 3-step "How it works" section with animated progress bar
- Pricing table with monthly/annual toggle
- Testimonials with star ratings
- CTA section with scroll-to-pricing
- Fully responsive (mobile hamburger menu)
- Smooth scroll-triggered fade-up animations

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| React 18 | UI library |
| Vite 5 | Dev server & bundler |
| Tailwind CSS 3 | Utility-first styling |
| Framer Motion | Scroll & entrance animations |
| Lucide React | Icons |

---

## Getting Started

### Prerequisites

- **Node.js** 18+ (recommended: 20 or 22)
- **npm** 9+ (comes with Node)

### Install & Run

```bash
# Clone the repo
git clone https://github.com/<your-username>/quill-landing.git
cd quill-landing

# Install dependencies
npm install

# Start dev server
npm run dev
```

The app will open at **http://localhost:5173**

### Build for Production

```bash
npm run build
```

Output goes to the `dist/` folder. Deploy it to any static host (Vercel, Netlify, GitHub Pages, etc.)

### Preview Production Build

```bash
npm run preview
```

---

## Project Structure

```
quill-landing/
  index.html
  package.json
  vite.config.js
  tailwind.config.js
  postcss.config.js
  src/
    main.jsx
    App.jsx
    index.css
    components/
      Navbar.jsx
      Hero.jsx
      LogoStrip.jsx
      Features.jsx
      Demo.jsx
      HowItWorks.jsx
      Pricing.jsx
      Testimonials.jsx
      CTA.jsx
      Footer.jsx
      Changelog.jsx
    hooks/
      useTypewriter.js
      useCountUp.js
```

---

## Customization

- **Colors**: Edit `tailwind.config.js` under `theme.extend.colors`
- **Fonts**: Change Google Fonts link in `index.html` and update `font-family` in `src/index.css`
- **Content**: Edit text directly in each component file under `src/components/`
- **Animations**: Tweak Framer Motion props (`transition`, `delay`, `viewport`) in components

---

## License

Free to use for personal and commercial projects.
