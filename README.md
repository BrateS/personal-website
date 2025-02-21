# Personal Portfolio Website

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A clean, modern portfolio website built with Astro and deployed on Cloudflare Workers. See it in action at [stefanbratescu.com](https://stefanbratescu.com/).

## Features

- ⚡️ Lightning-fast static site built with Astro
- 🎨 Clean, modern design with smooth animations
- 📱 Fully responsive layout
- 💻 Terminal-style sections for a unique developer feel
- 📅 Timeline-based experience display
- 🚀 Project showcase section
- 🎓 Education and skills overview with visual indicators
- ⬆️ Smooth scroll with back-to-top functionality
- ☁️ Easy deployment to Cloudflare Workers

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/BrateS/personal-website.git
cd personal-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Deployment with Cloudflare Workers

This site is configured for deployment on Cloudflare Pages using Workers. Here's how to deploy your own:

1. Install Wrangler CLI globally (if not already installed):
```bash
npm install -g wrangler
```

2. Login to your Cloudflare account:
```bash
wrangler login
```

3. Deploy to Cloudflare:
```bash
npm run deploy
```

The deployment configuration is handled in `wrangler.json`. The site will be built using Astro and deployed to Cloudflare's edge network.

## Customization

To make this portfolio your own:

1. Update `src/consts.ts` with your personal information:
   - Site title
   - Site description

2. Modify `src/pages/index.astro` to:
   - Update your profile information
   - Customize sections (experience, projects, education)
   - Adjust contact links

3. Replace `public/images/profile.jpg` with your photo

4. Customize styles in `src/styles/global.css`:
   - Color scheme (via CSS variables)
   - Typography
   - Layout preferences

## Technologies

- [Astro](https://astro.build/) - Static site builder
- CSS3 with custom properties
- Google Fonts (Lato & JetBrains Mono)
- Font Awesome icons
- Cloudflare Workers for hosting

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
