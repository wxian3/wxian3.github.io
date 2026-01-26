# Wenqi Xian - Personal Website

A personal academic website built with Jekyll, inspired by the [al-folio](https://github.com/alshedivat/al-folio) theme.

## 🚀 Quick Start

### Prerequisites

- Ruby (>= 2.7)
- Bundler

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **Open in browser:**
   Navigate to `http://localhost:4000`

## 📁 Project Structure

```
.
├── _config.yml          # Site configuration
├── _includes/           # Reusable HTML components
│   ├── header.html
│   └── footer.html
├── _layouts/            # Page layouts
│   ├── default.html
│   └── page.html
├── _pages/              # Additional pages
│   ├── publications.html
│   ├── projects.html
│   └── cv.html
├── assets/
│   ├── css/main.css     # Stylesheet
│   ├── img/             # Images
│   │   ├── profile.jpg  # Your profile photo
│   │   └── pubs/        # Publication thumbnails
│   └── pdf/             # PDF files (CV, papers)
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
└── README.md
```

## 🖼️ Adding Your Content

### Profile Photo
Add your profile photo as `assets/img/profile.jpg`

### Publication Thumbnails
Add publication images to `assets/img/pubs/`:
- `neural-lens.jpg`
- `factormatte.jpg`
- `stay-positive.jpg`
- `st-nerf.jpg`
- `crowdsampling.jpg`
- `uprightnet.jpg`
- `texturegan.jpg`
- `bdd100k.jpg`

### CV
Add your CV as `assets/pdf/cv.pdf`

## 🎨 Customization

### Colors
Edit the CSS variables in `assets/css/main.css`:

```css
:root {
  --color-primary: #b5121b;    /* Accent color */
  --color-text: #333;          /* Main text */
  --color-bg: #fafafa;         /* Background */
}
```

### Fonts
The site uses:
- **Libre Baskerville** - Headings (serif)
- **Source Sans Pro** - Body text (sans-serif)

Change fonts in `_layouts/default.html` and `assets/css/main.css`.

## 🌐 Deployment (GitHub Pages)

1. Push to your GitHub repository
2. Go to Settings → Pages
3. Select source: `main` branch
4. Your site will be live at `https://yourusername.github.io`

## 📝 License

MIT License

---

Built with ❤️ using [Jekyll](https://jekyllrb.com/)
