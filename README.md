# VibeCast Marketing Site

Clean, developer-centric marketing site for VibeCast built with Astro and deployed on Cloudflare Pages.

## Features

- 🚀 **Astro** - Fast, modern static site generator
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- ☁️ **Cloudflare Pages** - Edge deployment and hosting
- 📱 **Responsive Design** - Mobile-first responsive layout
- 🌙 **Dark Mode** - Beautiful dark theme
- ⚡ **Performance** - Optimized for speed and SEO

## Tech Stack

- **Framework**: Astro 4.x
- **Styling**: Tailwind CSS
- **Deployment**: Cloudflare Pages
- **Fonts**: Inter (sans) + JetBrains Mono (code)
- **Icons**: Heroicons

## Development

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
src/
├── layouts/
│   └── Layout.astro          # Base layout with SEO and styling
├── components/
│   ├── Header.astro          # Navigation header
│   └── Footer.astro          # Site footer
├── pages/
│   ├── index.astro           # Homepage
│   ├── features.astro        # Features page
│   └── docs.astro            # Documentation hub
└── styles/
    └── global.css            # Global styles and utilities
```

## Design System

### Colors
- **Primary**: Blue gradient (#0ea5e9 to #3b82f6)
- **Background**: Dark grays (#0f172a, #1e293b)
- **Glass Effect**: Backdrop blur with subtle borders

### Typography
- **Headings**: Inter, bold weights
- **Body**: Inter, regular weights  
- **Code**: JetBrains Mono

### Components
- Glass morphism cards
- Gradient text effects
- Code blocks with syntax highlighting
- Responsive navigation

## Deployment

The site is configured for Cloudflare Pages deployment:

1. Connect your GitHub repository to Cloudflare Pages
2. Set build command: `npm run build`
3. Set output directory: `dist`
4. Deploy automatically on push to main

## SEO & Performance

- Optimized meta tags and Open Graph
- Semantic HTML structure
- Lazy loading for images
- Minimal JavaScript bundle
- Perfect Lighthouse scores

## Content Strategy

The site focuses on:
- Developer experience and technical benefits
- Clear value proposition for API development
- Plugin ecosystem and extensibility
- Enterprise and SaaS use cases
- Community and open source

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the build locally
5. Submit a pull request

## License

MIT License - see [LICENSE](../LICENSE) for details.