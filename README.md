# RAG AI Solutions Website

Enterprise AI solutions powered by Retrieval-Augmented Generation technology.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/daitluong/daitluong.github.io.git
cd daitluong.github.io
```

2. Install dependencies:
```bash
npm install
```

### Development

#### Build Tailwind CSS (Production)
```bash
npm run build:css
```

#### Watch Mode (Development)
```bash
npm run watch:css
```

This will watch for changes in your HTML and CSS files and automatically rebuild the Tailwind CSS.

## 📁 Project Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Compiled Tailwind CSS (generated)
├── src/
│   └── input.css       # Tailwind source file
├── tailwind.config.js  # Tailwind configuration
├── package.json        # Node dependencies
├── robots.txt          # SEO: Search engine crawler instructions
├── sitemap.xml         # SEO: Site structure for search engines
└── assets/             # Images, icons, etc.
```

## 🎨 Using Tailwind CSS

### Custom Colors
The project uses custom color schemes defined in `tailwind.config.js`:
- **Primary**: `#667eea` (purple/blue)
- **Secondary**: `#764ba2` (purple)
- **Dark**: `#2d3748`

Use them in your HTML:
```html
<div class="bg-primary text-white">Hello</div>
<button class="bg-primary-dark hover:bg-primary">Click me</button>
```

### Custom Animations
Available animations:
- `animate-fadeInUp` - Fade in with upward motion
- `animate-fadeInDown` - Fade in with downward motion

With delays:
- `animate-delay-200` - 0.2s delay
- `animate-delay-400` - 0.4s delay

### Responsive Design
Tailwind uses mobile-first breakpoints:
```html
<div class="text-sm md:text-base lg:text-lg">Responsive text</div>
```

## 🔧 Customization

### Modifying Tailwind Configuration
Edit `tailwind.config.js` to customize:
- Colors
- Fonts
- Spacing
- Breakpoints
- Animations

### Adding Custom Styles
Add custom CSS in `src/input.css`:
```css
@layer components {
  .my-custom-class {
    @apply bg-primary text-white rounded-lg p-4;
  }
}
```

Then rebuild:
```bash
npm run build:css
```

## 📦 Deployment

### GitHub Pages
1. Make sure `styles.css` is committed (not in .gitignore)
2. Push changes to the `main` branch
3. The site will automatically deploy to `https://daitluong.github.io`

### Before Deploying
```bash
# Build production CSS
npm run build:css

# Commit changes
git add .
git commit -m "Update styles"
git push origin main
```

## 🔍 SEO Features

- ✅ Meta tags for social media (Open Graph, Twitter Cards)
- ✅ Structured data (JSON-LD) for rich snippets
- ✅ robots.txt for search engine crawlers
- ✅ sitemap.xml for better indexing
- ✅ Canonical URLs
- ✅ Mobile-friendly and responsive

## 🍪 Cookie Consent

The website includes a region-aware cookie consent banner that complies with:
- **GDPR** (EU)
- **CCPA** (California)
- **LGPD** (Brazil)
- **PIPL** (China)

The banner automatically detects the visitor's region and displays the appropriate message.

## 📝 Scripts

| Script | Description |
|--------|-------------|
| `npm run build:css` | Build Tailwind CSS for production (minified) |
| `npm run watch:css` | Watch for changes and rebuild automatically |
| `npm run dev` | Alias for `watch:css` |

## 🛠️ Technologies

- **Tailwind CSS 3.4+** - Utility-first CSS framework
- **Vanilla JavaScript** - Cookie consent & interactions
- **HTML5** - Semantic markup
- **GitHub Pages** - Hosting

## 📄 License

MIT License - see LICENSE file for details

## 👥 Author

RAG AI Solutions - Powered by FireFlyDevOps, LLC

---

For questions or support, contact: contact@rag-ai-solutions.com
