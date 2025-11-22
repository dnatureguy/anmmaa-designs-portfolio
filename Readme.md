# ANMMAA Designs Website

A modern, custom-built website for ANMMAA Designs - Interior & Exterior Design company.

## Project Structure

```
anmmaa-designs/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Your project images (create this folder)
└── README.md           # This file
```

## Setup Instructions

### 1. Create the Project Structure

In your terminal or file explorer, create the following structure:

```bash
mkdir anmmaa-designs
cd anmmaa-designs
mkdir css js images
```

### 2. Create the Files

Create these files and copy the code I provided:
- `index.html` - The main HTML structure
- `css/styles.css` - All the styling
- `js/main.js` - JavaScript functionality

### 3. Add Your Images

1. Place your project images in the `images/` folder
2. In `index.html`, replace the placeholder image URLs:
   - Change `YOUR_IMAGE_URL_1` to `images/your-image-name.jpg`
   - Example: `<img src="images/living-room.jpg" alt="Modern Living Room">`

### 4. Test Locally

Open `index.html` in your browser to test the site.

### 5. Initialize Git

```bash
git init
git add .
git commit -m "Initial commit: ANMMAA Designs website"
```

### 6. Push to GitHub

```bash
# Create a new repository on GitHub first, then:
git remote add origin https://github.com/yourusername/anmmaa-designs.git
git branch -M main
git push -u origin main
```

## Color Palette

- **Navy Blue**: #193a4c (Primary background)
- **Bright Yellow**: #fdec00 (Accent color)
- **White**: #ffffff (Text)
- **Dark Charcoal**: #0f2430 (Secondary background)

## Features

- ✨ Smooth scroll navigation
- 📱 Fully responsive design
- 🎨 Modern animations and transitions
- 📧 Contact form (needs backend integration)
- 🖼️ Portfolio gallery with hover effects
- 🎯 SEO-friendly structure

## Deployment Options

### GitHub Pages (Free)
1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/anmmaa-designs`

### Netlify (Free)
1. Drag and drop your project folder to netlify.com
2. Instant deployment with custom domain support

### Vercel (Free)
1. Import your GitHub repository
2. Automatic deployments on every push

## Customization

### Changing Colors
Edit `css/styles.css` and update the color values:
- Primary: `#193a4c`
- Accent: `#fdec00`

### Adding Pages
Create new HTML files (e.g., `services.html`, `about.html`) and link them in the navigation.

### Contact Form Backend
The form currently shows an alert. To make it functional:
1. Use a service like Formspree, EmailJS, or Netlify Forms
2. Update the form submission handler in `js/main.js`

## Next Steps

- [ ] Add your actual project images
- [ ] Set up contact form backend
- [ ] Add more pages (individual service pages, project details)
- [ ] Implement image lightbox for portfolio
- [ ] Add testimonials section
- [ ] Set up analytics (Google Analytics)
- [ ] Add SEO meta tags

## Support

For questions or issues, feel free to reach out!

---

Built with ❤️ for ANMMAA Designs