# The New Architect Blog

A modern, responsive blog built with HTMX and Tailwind CSS, designed for GitHub Pages.

## Features

- 🎨 **Modern UI**: Beautiful, responsive design using Tailwind CSS
- ⚡ **HTMX Integration**: Dynamic interactions without complex JavaScript
- 📱 **Mobile-First**: Fully responsive across all devices
- 🚀 **GitHub Pages Ready**: Optimized for static hosting
- 📝 **Blog Posts**: Sample blog posts included to get you started

## Tech Stack

- **HTMX**: For dynamic HTML interactions
- **Tailwind CSS**: For styling via CDN
- **Font Awesome**: For icons
- **GitHub Pages**: For hosting

## Getting Started

### Local Development

1. Clone this repository:
```bash
git clone <your-repo-url>
cd The-New-Architect-Blog
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

### Deploying to GitHub Pages

1. Push your code to a GitHub repository

2. Go to your repository settings on GitHub

3. Navigate to **Pages** in the left sidebar

4. Under **Source**, select:
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`

5. Click **Save**

6. Your site will be available at:
   ```
   https://<username>.github.io/The-New-Architect-Blog/
   ```

### Custom Domain (Optional)

1. Add a `CNAME` file in the root directory with your domain:
   ```
   yourdomain.com
   ```

2. Configure DNS settings with your domain provider:
   - Type: `CNAME`
   - Name: `@` or `www`
   - Value: `<username>.github.io`

## Project Structure

```
The-New-Architect-Blog/
├── index.html              # Main blog listing page
├── posts/                  # Blog post directory
│   ├── microservices-patterns.html
│   ├── ci-cd-best-practices.html
│   └── api-security.html
├── README.md               # This file
└── LICENSE                 # License file
```

## Customization

### Adding New Blog Posts

1. Create a new HTML file in the `posts/` directory
2. Use one of the existing posts as a template
3. Update the `index.html` file to include your new post in the blog listing

### Styling

The project uses Tailwind CSS via CDN. You can customize colors and styles by:
- Modifying Tailwind classes directly in HTML
- Adding custom CSS in a `<style>` tag
- Using Tailwind's configuration (requires build process)

### HTMX Features

The blog includes HTMX examples:
- Like button interactions (requires backend for full functionality)
- Dynamic content loading capabilities

To add more HTMX features, refer to the [HTMX documentation](https://htmx.org/docs/).

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- [HTMX](https://htmx.org/) - For making dynamic HTML simple
- [Tailwind CSS](https://tailwindcss.com/) - For the utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) - For the icons
