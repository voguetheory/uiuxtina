# Portfolio Site

A minimal, clean portfolio site for a Senior UI/UX & Product Designer built with Astro.

## Features

- **Dark Theme**: Professional dark design with muted warm orange/amber accent (#CC8866)
- **Minimal & Clean**: Focus on content with thoughtful whitespace and typography
- **Subtle Animations**: Fade-in effects and smooth transitions
- **Responsive**: Works beautifully on all device sizes
- **Fast**: Built with Astro for optimal performance

## Sections

- Hero / Introduction
- About / Bio with skills
- Contact Form (UI ready, needs integration)

## Getting Started

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run dev
```

Visit `http://localhost:4321` to view your site.

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Customization

### Content

Edit the component files in `src/components/` to update:
- `Hero.astro` - Your name, title, and introduction
- `About.astro` - Bio, skills, and expertise
- `Contact.astro` - Contact form text
- `Footer.astro` - Social media links

### Styling

Colors and spacing are defined as CSS custom properties in `src/layouts/Layout.astro`:
- `--color-accent` - Main accent color (currently #CC8866)
- Adjust spacing, fonts, and other design tokens as needed

### Contact Form Integration

The contact form UI is ready. To wire it up, choose one of these options:

1. **FormSpree** - Add action URL to the form
2. **Netlify Forms** - Add `netlify` attribute to form
3. **Custom Backend** - Update the form submission handler in `Contact.astro`

## Deployment

This site can be deployed to:
- Netlify
- Vercel
- Cloudflare Pages
- GitHub Pages
- Any static hosting service

Follow [Astro's deployment guide](https://docs.astro.build/en/guides/deploy/) for your platform of choice.
