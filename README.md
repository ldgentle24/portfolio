# Portfolio Site

A minimalist, dark-themed portfolio site built with Astro.

## Features

- **Dark-only theme** - Clean black background with white text
- **Minimal navigation** - Simple, intuitive navigation
- **Responsive design** - Mobile-first approach that scales beautifully
- **Fast performance** - Static-first with minimal JavaScript
- **Project showcase** - Dedicated pages for each project

## Structure

```
portfolio-site/
├── src/
│   ├── layouts/
│   │   ├── BaseLayout.astro      # Global HTML shell
│   │   └── PageLayout.astro      # Shared page wrapper
│   ├── components/
│   │   ├── Nav.astro             # Navigation component
│   │   └── ProjectCard.astro     # Project card component
│   ├── pages/
│   │   ├── index.astro           # Homepage
│   │   ├── work.astro            # Work index page
│   │   ├── work/                 # Individual project pages
│   │   ├── about.astro           # About page
│   │   └── contact.astro         # Contact page
│   └── styles/
│       ├── global.css            # Reset & base styles
│       ├── typography.css        # Type scale
│       └── layout.css            # Spacing & grids
└── public/                       # Static assets
```

## Getting Started

### Install dependencies

```bash
npm install
```

### Start dev server

```bash
npm run dev
```

The site will be available at `http://localhost:4321/`

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Pages

- **Homepage** - Hero section with centered text
- **Work** - Grid of project cards
- **Individual Projects** - Detailed project pages with consistent structure
- **About** - Personal/professional bio
- **Contact** - Contact information and social links

## Customization

### Update Content

1. Edit project information in `src/pages/work.astro`
2. Update individual project pages in `src/pages/work/`
3. Modify about content in `src/pages/about.astro`
4. Update contact details in `src/pages/contact.astro`

### Add Images/Videos

Place media files in `src/assets/` and reference them in your project pages.

### Styling

- Global styles: `src/styles/global.css`
- Typography: `src/styles/typography.css`
- Layout utilities: `src/styles/layout.css`

## Design Principles

- **Cold, intentional, slightly intimidating** - Like a gallery where you lower your voice
- **No autoplay media** - Respect user preferences
- **Fast load times** - Minimal JavaScript, optimized assets
- **Clean code** - No overengineering, simple and maintainable

## Deployment

This site can be deployed to:
- Vercel
- Netlify
- Cloudflare Pages
- GitHub Pages

All support Astro's static output out of the box.

## License

MIT
