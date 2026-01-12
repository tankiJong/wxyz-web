# WxYZ Foundation Website

A sleek, dark-themed static website for WxYZ Foundation built with [Astro](https://astro.build).

## Features

- **Modern Dark Theme** - Cyberpunk-inspired design with electric cyan and magenta accents
- **Terminal Aesthetics** - Monospace fonts and command-line inspired elements
- **Responsive Design** - Fully responsive across all devices
- **Smooth Animations** - Subtle fade-ins and hover effects
- **Fast Performance** - Static site generation for blazing fast load times

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or pnpm

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Design System

### Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Background Primary | `#0a0a0f` | Main background |
| Background Secondary | `#12121a` | Cards, sections |
| Accent Cyan | `#00f0ff` | Primary accent, links |
| Accent Magenta | `#ff00aa` | Secondary accent |
| Text Primary | `#f0f0f0` | Headings, main text |
| Text Secondary | `#a0a0b0` | Body text |

### Typography

- **Logo**: Fira Code (monospace)
- **Headings**: Outfit
- **Body**: Outfit

## License

© 2026 WxYZ Foundation. All rights reserved.
