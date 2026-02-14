# SalixWen's Technical Blog

A minimalist personal technical blog featuring web development insights, system architecture discussions, WebGL graphics programming, and security research. Built with a focus on clarity, performance, and user experience.

![Website Preview](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

- **Minimal Design** — Clean, distraction-free interface with thoughtful typography
- **Dark/Light Mode** — Classic iOS-style toggle with smooth transitions
- **Typing Animation** — Dynamic hero section with typewriter effect
- **Blog System** — Markdown-powered articles with syntax highlighting
- **Tag Filtering** — Browse articles by category (WebGL, Frontend, Architecture, Security)
- **Search** — Real-time article search functionality
- **Performance Optimized** — Lazy loading, code splitting, and smooth scrolling
- **SEO Ready** — Meta tags, Open Graph, and structured data

## 🚀 Getting Started

### View Online

Visit the live site: [https://salixwen.com](https://salixwen.com)

### Local Development

```bash
# Clone the repository
git clone https://github.com/SalixJFrost/SalixJFrost.github.io.git

# Navigate to project directory
cd SalixJFrost.github.io

# Open in browser (using Python)
python -m http.server 8000

# Or open directly
open index.html
```

## 📁 Project Structure

```
SalixJFrost.github.io/
├── index.html          # Main blog with SPA routing
├── about/
│   └── index.html      # About page
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

## 🛠️ Tech Stack

- **HTML5** — Semantic markup with accessibility support
- **CSS3** — Custom properties, animations, responsive design
- **JavaScript** — Vanilla JS SPA with no dependencies
- **Marked.js** — Markdown parsing
- **Prism.js** — Syntax highlighting
- **Google Fonts** — DM Sans & Playfair Display

## 📝 Adding New Posts

Edit the `posts` array in `index.html`:

```javascript
{
  title: 'Your Post Title',
  tags: ['Category1', 'Category2'],
  date: '2026-02-14',
  content: `
# Your Title

Your content here with **Markdown** support.
`
}
```

## 🎨 Customization

### Theme Colors

Modify CSS variables in `:root`:

```css
:root {
  --accent-primary: #1d9bf0;
  --card-bg: rgba(255, 255, 255, 0.8);
}
```

### Typography

Change fonts in the Google Fonts link:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;700&display=swap" rel="stylesheet">
```

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## 🔐 Security

This blog follows security best practices:
- Content Security Policy headers
- No external tracking scripts
- Secure font loading
- Accessible HTTPS

## 📄 License

MIT License — Feel free to use this template for your own blog.

## 🙋‍♂️ Author

**SalixWen** — Developer & Technical Writer

- GitHub: [@SalixJFrost](https://github.com/SalixJFrost)
- Website: [https://salixwen.com](https://salixwen.com)

## 🙏 Acknowledgments

- Inspired by minimal design principles
- Typography: [DM Sans](https://fonts.google.com/specimen/DM+Sans) & [Playfair Display](https://fonts.google.com/specimen/Playfair+Display)
- Icons: Custom CSS implementations

---

*Built with ❤️ and attention to detail*
