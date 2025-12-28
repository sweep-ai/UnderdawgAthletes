# Underdawg Athletes - Website Funnel

A modern, fully responsive website for Underdawg Athletes featuring smooth scroll animations, desktop optimization, and interactive navigation.

## Features

- ✅ Fully responsive design (mobile & desktop optimized)
- ✅ Smooth scroll animations
- ✅ Interactive navigation with scroll routing
- ✅ Button functionality throughout
- ✅ Lead magnet form
- ✅ Package selection system
- ✅ Dark mode support

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - No dependencies required
- **Material Icons** - Icon library

## Local Development

Simply open `index.html` in your web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. For production deployment:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. Push your code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will auto-detect it as a static site
6. Click "Deploy"

### Option 3: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Drag and drop the project folder or connect via Git
4. Vercel will automatically detect the static site
5. Click "Deploy"

## Project Structure

```
WebsiteFunnel/
├── index.html              # Main website file
├── vercel.json            # Vercel configuration
├── .gitignore            # Git ignore rules
├── README.md             # This file
└── stitch_hero_section_underdog_athletes/  # Component source files
    └── ...
```

## Configuration

The `vercel.json` file includes:
- Static site configuration
- Security headers (XSS protection, frame options, etc.)
- Cache control for HTML files
- Route configuration for SPA-like behavior

## Customization

### Update Branding
- Search and replace "Underdawg" throughout `index.html` if needed
- Update colors in the Tailwind config section (primary color: `#e42121`)

### Modify Animations
- Animation classes: `.fade-in`, `.slide-in-left`, `.slide-in-right`, `.scale-in`
- Adjust delays: `.delay-100` through `.delay-500`
- Modify transition duration in the `<style>` section

### Update Content
- All content is in `index.html`
- Sections are clearly marked with IDs for easy navigation

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Underdawg Athletes. All rights reserved.

