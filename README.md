# Poornachandra G. - Portfolio Website

A high-quality, professional portfolio website showcasing my experience as a Lead Bioinformatician specializing in Precision Medicine, NGS Pipelines, and ML/AI for Clinical Genomics.

## 🌐 Live Demo

Visit the live website: `https://<your-username>.github.io/Portifolio/`

## ✨ Features

- **Modern Dark Theme** - BioTech Elegance design with DNA-inspired aesthetics
- **Fully Responsive** - Optimized for all screen sizes
- **Smooth Animations** - Scroll-triggered animations and micro-interactions
- **Fast Loading** - Pure HTML/CSS/JS, no frameworks required
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Accessible** - Keyboard navigation and ARIA labels

## 📂 Project Structure

```
Portifolio/
├── index.html           # Main single-page website
├── css/
│   └── styles.css       # All styles with CSS variables
├── js/
│   └── main.js          # Animations and interactions
├── assets/
│   └── images/          # Future: profile photos, project screenshots
├── Resume_Poornachandra_G_v3.pdf  # Downloadable resume
└── README.md            # This file
```

## 🚀 Deployment to GitHub Pages

### Option 1: Deploy from Main Branch

1. **Push code to GitHub**
   ```bash
   git add .
   git commit -m "Add portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

3. **Access your site**
   - Your site will be available at `https://<username>.github.io/Portifolio/`
   - It may take a few minutes for the first deployment

### Option 2: Using GitHub Actions (Recommended)

Create `.github/workflows/deploy.yml` for automatic deployments.

## 🛠️ Local Development

### Using Python HTTP Server
```bash
cd Portifolio
python -m http.server 8080
# Open http://localhost:8080 in your browser
```

### Using Node.js
```bash
npx serve .
# Open the provided URL in your browser
```

### Using VS Code Live Server
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎨 Customization

### Colors
Edit CSS custom properties in `css/styles.css`:
```css
:root {
    --color-accent-primary: #00d4ff;    /* Cyan accent */
    --color-accent-secondary: #7c3aed;  /* Purple accent */
    --color-accent-tertiary: #ec4899;   /* Pink accent */
}
```

### Content
Update the following sections in `index.html`:
- Hero section with your name and tagline
- About section with your summary
- Experience timeline with your career history
- Skills section with your competencies
- Projects section with your work
- Publications section with your papers
- Contact section with your details

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

© 2024 Poornachandra G. All rights reserved.

## 📬 Contact

- **Email**: poornachandra.gedi@gmail.com
- **LinkedIn**: [linkedin.com/in/poornachandra-g](https://linkedin.com/in/poornachandra-g)
- **ORCID**: [0009-0009-1610-1205](https://orcid.org/0009-0009-1610-1205)
