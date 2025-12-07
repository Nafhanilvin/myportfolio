# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- 📱 Fully responsive design
- 🎨 Modern and clean UI
- ⚡ Fast and lightweight
- 🎯 Smooth scrolling navigation
- 💼 Projects showcase
- 📧 Contact form
- 🌐 Ready to deploy

## Customization

### Update Your Information

1. **Personal Information** - Edit `index.html`:
   - Line 33: Update "Your Name" in the hero section
   - Line 34: Update your role/title
   - Lines 169-183: Update contact information (email, phone, location)
   - Line 184-186: Update social media links
   - Line 213: Update footer copyright

2. **About Section** - Edit `index.html` lines 53-57:
   - Replace the paragraphs with your own bio

3. **Skills** - Edit `index.html` lines 66-110:
   - Customize the skill cards with your own skills

4. **Projects** - Edit `index.html` lines 118-165:
   - Replace with your actual projects
   - Add project images (replace `.image-placeholder` divs)
   - Update project descriptions and links

5. **Colors** - Edit `styles.css` lines 9-18:
   - Customize the CSS variables to change the color scheme

### Adding Images

Replace the `.image-placeholder` divs with actual images:

```html
<!-- Replace this: -->
<div class="image-placeholder">Your Photo</div>

<!-- With this: -->
<img src="your-photo.jpg" alt="Your Name">
```

## Local Development

1. Open the folder in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server" (install Live Server extension if needed)

Or simply open `index.html` in your browser.

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. Create a new GitHub repository
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Select "main" branch as source
5. Your site will be live at `https://yourusername.github.io/portfolio`

### Option 2: Netlify (Free)

1. Sign up at [netlify.com](https://www.netlify.com)
2. Drag and drop your portfolio folder
3. Your site will be live instantly with a free domain

### Option 3: Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com)
2. Install Vercel CLI: `npm i -g vercel`
3. Run `vercel` in your project folder
4. Follow the prompts

### Option 4: Cloudflare Pages (Free)

1. Sign up at [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repository
3. Deploy automatically

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── .gitignore         # Git ignore file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio!

## Next Steps

1. ✅ Customize all content with your information
2. ✅ Add your actual projects and descriptions
3. ✅ Replace placeholder images with real images
4. ✅ Update colors to match your personal brand
5. ✅ Test the contact form functionality
6. ✅ Deploy to your hosting platform of choice
7. ✅ Share your portfolio with the world!

---

Built with ❤️ using HTML, CSS, and JavaScript
