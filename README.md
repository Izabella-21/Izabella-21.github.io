# Izabella Molnar - Portfolio

A clean, modern portfolio website built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Prerequisites
- Ruby 3.1.4+
- Bundler

### Installation & Setup

```bash
# Clone the repository
git clone <repo-url>
cd my-portfolio

# Install dependencies
bundle install

# Start the development server
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site locally.

## 📁 Project Structure

```
my-portfolio/
├── _layouts/              # Jekyll layout templates
│   └── fullwidth.html     # Main layout with custom styling
├── _posts/                # Blog posts
├── _data/                 # Navigation and site data
├── _config.yml            # Jekyll configuration
├── assets/
│   ├── css/              # Stylesheets
│   └── fonts/            # Custom fonts (Satoshi)
├── index.md              # Home page
├── resume.md             # Resume page
├── portfolio.md          # Portfolio page
├── blog.md               # Blog page
└── Gemfile               # Ruby dependencies
```

## 🎨 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Dark Mode Support** - Automatic theme detection with CSS variables
- **Custom Typography** - Uses Plus Jakarta Sans and Satoshi fonts
- **Smooth Animations** - Scroll reveal effects on page elements
- **Fast Performance** - Optimized font loading and minimal CSS

## 🛠 Build & Deploy

### Local Development
```bash
bundle exec jekyll serve
```
The site rebuilds automatically on file changes.

### Production Build
```bash
bundle exec jekyll build
```
Output is generated in the `_site/` directory.

### GitHub Pages Deployment
Push to your `main` branch and GitHub Actions will automatically build and deploy.

## 📝 Customization

### Site Configuration
Edit `_config.yml` to update:
- Site title and description
- Navigation links (via `_data/navigation.yml`)
- Jekyll theme settings

### Styling
Main styles are in `_layouts/fullwidth.html`. Customize:
- Color scheme (CSS variables under `:root`)
- Typography
- Layout spacing

### Content
- **Home**: `index.md`
- **Resume**: `resume.md`
- **Portfolio**: `portfolio.md`
- **Blog**: `blog.md` (individual posts in `_posts/`)

## 🚫 Ignored Files

The following are excluded from the repository:
- `_site/` - Generated build artifacts
- `.jekyll-cache/` - Build cache
- `.bundle/` - Bundled gems
- `Gemfile.lock` - For flexibility across environments

## 📦 Dependencies

- **Jekyll** - Static site generator
- **Minimal Mistakes Theme** - Remote theme for base styling
- **Plugins**:
  - jekyll-feed - RSS feed generation
  - jekyll-sitemap - Sitemap generation
  - jekyll-paginate - Post pagination
  - jekyll-include-cache - Include caching

## ⚡ Performance Tips

- Fonts use `font-display: swap` for faster text rendering
- CSS variables enable efficient theming
- Minimal JavaScript for fast page loads
- Remote theme reduces file size

## 📄 License

This portfolio is open source and available under the MIT License.

## 👤 Author

**Izabella Molnar**
- Email: m.izabella21@gmail.com
- GitHub: [@Izabella-21](https://github.com/Izabella-21)
- LinkedIn: [izabella-molnar](https://www.linkedin.com/in/izabella-molnar/)
