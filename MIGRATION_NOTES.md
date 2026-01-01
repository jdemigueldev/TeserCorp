# TeserCorp Website - Astro Migration

## Overview
The TeserCorp website has been successfully migrated from static HTML to Astro framework.

## What Was Migrated
- **index.html** → `src/pages/index.astro` (main landing page with tabbed interface)
- **artista.html** → `src/pages/artista.astro` (artist detail page)
- **evento.html** → `src/pages/evento.astro` (event detail page)
- **merch.html** → `src/pages/merch.astro` (merch detail page)
- **post.html** → `src/pages/post.astro` (blog post page)

## Project Structure
```
TeserCorp/
├── src/
│   ├── pages/          # Astro pages
│   ├── layouts/        # Layout templates
│   └── components/     # Reusable components
├── public/             # Static assets
├── astro.config.mjs    # Astro configuration
├── package.json        # Dependencies
└── tsconfig.json       # TypeScript configuration
```

## Key Features Preserved
- ✅ Tailwind CSS CDN configuration
- ✅ Custom color palette (industrial theme)
- ✅ Tab-based navigation on home page
- ✅ Dynamic content via URL parameters
- ✅ All interactive JavaScript functionality
- ✅ Responsive design
- ✅ All original styling and animations

## Development Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Deployment
The `dist/` folder contains the built static site ready for deployment. The CNAME file is automatically included in the build.

## Notes
- Original HTML files remain in the repository root for reference
- All assets have been moved to the `public/` directory
- The site uses Tailwind CSS CDN for styling (no build step required for CSS)
