# Hugo Website Workshop Template

This is a clean Hugo website template for workshops. It's based on the Hugoplate theme and includes a modern, responsive design with Tailwind CSS.

## 🚀 Quick Start

### Prerequisites
- [Hugo Extended](https://gohugo.io/installation/) (version 0.100.0 or higher)
- [Node.js](https://nodejs.org/) (version 16 or higher)
- [Git](https://git-scm.com/)

### Installation Steps

1. **Clone this repository**
   ```bash
   git clone <your-repo-url>
   cd hugoplate
   ```

2. **Install Node.js dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   hugo server
   ```

4. **Open your browser**
   Navigate to `http://localhost:1313`

## 📁 Project Structure

```
hugoplate/
├── assets/              # Source files (CSS, JS, images)
├── content/             # Your content (blog posts, pages)
├── data/                # Site configuration data
├── themes/              # Hugo theme files
├── hugo.toml           # Hugo configuration
├── package.json        # Node.js dependencies
└── tailwind-plugin/    # Custom Tailwind components
```

## 🎨 Customization

### Site Configuration
Edit `hugo.toml` to customize:
- Site title and description
- Theme settings
- Build options
- Permalinks

### Content
- **Blog posts**: Add markdown files in `content/english/blog/`
- **Pages**: Create new markdown files in `content/english/`
- **Images**: Place images in `assets/images/`

### Styling
- **CSS**: Modify `assets/scss/` files
- **Tailwind**: Customize `tailwind.config.js`
- **Components**: Edit files in `themes/hugoplate/layouts/partials/`

## 🔧 Development

### Available Scripts
```bash
# Start development server
hugo server

# Build for production
hugo

# Build with drafts
hugo --buildDrafts

# Build with future posts
hugo --buildFuture
```

### Theme Development
The theme is located in `themes/hugoplate/`. You can:
- Modify layouts in `layouts/`
- Update styles in `assets/`
- Customize partials in `layouts/partials/`

## 📱 Features

- ✅ Responsive design
- ✅ Dark/Light mode toggle
- ✅ Blog functionality
- ✅ Search capability
- ✅ SEO optimized
- ✅ Fast loading
- ✅ Mobile friendly

## 🚀 Deployment

### Netlify
1. Push to GitHub
2. Connect repository to Netlify
3. Build command: `hugo`
4. Publish directory: `public`

### Vercel
1. Push to GitHub
2. Import repository to Vercel
3. Build command: `hugo`
4. Output directory: `public`

### GitHub Pages
1. Enable GitHub Pages in repository settings
2. Use GitHub Actions workflow (see `.github/workflows/`)

## 🐛 Troubleshooting

### Common Issues

**"Hugo command not found"**
- Install Hugo Extended from [gohugo.io](https://gohugo.io/installation/)

**"Node modules not found"**
- Run `npm install` to install dependencies

**"Theme not found"**
- Ensure the `themes/hugoplate/` directory exists
- Check `hugo.toml` theme setting

**"Build errors"**
- Check Hugo version compatibility
- Verify all required files are present

### Getting Help
- [Hugo Documentation](https://gohugo.io/documentation/)
- [Hugoplate Theme](https://hugoplate.netlify.app/)
- [Tailwind CSS](https://tailwindcss.com/docs)

## 📝 Workshop Activities

1. **Setup & Installation** (15 min)
   - Install prerequisites
   - Clone and setup project

2. **Content Creation** (30 min)
   - Create a new blog post
   - Add images and formatting
   - Customize metadata

3. **Styling & Layout** (30 min)
   - Modify CSS variables
   - Customize components
   - Add custom styles

4. **Deployment** (15 min)
   - Build the site
   - Deploy to hosting platform

## 🎯 Learning Objectives

By the end of this workshop, students will:
- Understand Hugo's static site generation
- Know how to create and manage content
- Be able to customize themes and layouts
- Have a deployed website to showcase

## 📚 Additional Resources

- [Hugo Quick Start](https://gohugo.io/getting-started/quick-start/)
- [Markdown Guide](https://www.markdownguide.org/)
- [CSS Grid Layout](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

---

**Happy coding! 🎉**

If you have questions or run into issues, check the troubleshooting section above or ask your workshop instructor.
