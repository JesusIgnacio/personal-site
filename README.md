# Flexoki Personal Site

A minimal personal website built with [Eleventy](https://www.11ty.dev/) and styled with the [Flexoki](https://stephango.com/flexoki) color palette.

## Features

- 🎨 Beautiful Flexoki color scheme with automatic dark/light mode
- 📱 Fully responsive design
- ⚡ Fast static site generation with Eleventy
- 📝 Markdown-based content management
- 🔍 SEO optimized with meta tags
- 📖 Blog post collection with date sorting

## Development

### Prerequisites

- Node.js (v16 or higher)
- npm

### Setup

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Clean build directory
npm run clean
```

The site will be available at `http://localhost:8080` during development.

## Project Structure

```
├── _includes/          # Nunjucks templates
│   └── layout.njk     # Base layout template
├── _site/             # Generated site (build output)
├── css/               # Stylesheets
│   └── style.css      # Main CSS file
├── posts/             # Blog posts (Markdown)
├── .eleventy.js       # Eleventy configuration
├── index.md           # Homepage
├── about.md           # About page
├── now.md             # Now page
├── posts.md           # Posts index
└── package.json       # Dependencies and scripts
```

## Customization

- **Colors**: Edit CSS custom properties in `css/style.css`
- **Typography**: Change the `--font-base` variable or update Google Fonts link
- **Content**: Edit Markdown files or create new ones
- **Layout**: Modify `_includes/layout.njk`

## Deployment

This site can be deployed to any static hosting service:

- **Netlify**: Connect your Git repository and set build command to `npm run build`
- **Vercel**: Import project and it will auto-detect Eleventy
- **GitHub Pages**: Use GitHub Actions with Eleventy build process

## License

MIT
