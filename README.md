# qer.at

A clean, minimal personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## Features

- **Responsive Design** - Mobile-first approach ensuring great experience on all devices
- **Interactive Art Gallery** - Full-screen image viewer with keyboard and mouse navigation
- **Smooth Animations** - Animated button effects and hover states
- **Optimized Structure** - Well-organized asset management with separate folders for documents and images
- **Accessible** - Semantic HTML and ARIA labels for better accessibility
- **Fast Loading** - Lightweight, no external dependencies or frameworks

## Project Structure

```
qer.at/
├── index.html              # Home page (entry point)
├── me.html                 # About me section
├── now.html                # Current activities
├── projects.html           # Portfolio of projects
├── art.html                # Interactive photo gallery
├── links.html              # Curated collection of links
├── css/
│   └── style.css          # Main stylesheet with earth-tone palette
└── assets/
    ├── documents/
    │   ├── Tareq_Derdaki_CV.pdf
    │   └── Tareq_Derdaki_Resume.pdf
    └── images/
        ├── favicon.png
        ├── coding-goblin.gif
        ├── leonard_cohen_mural.jpeg
        ├── man_walking.gif
        ├── tareq.jpg
        └── website_images/
            └── (36 photography images)
```

## Pages Overview

### Index (`index.html`)
Landing page with typewriter animation introducing the site

### About (`me.html`)
Personal information with portrait and links to relevant sections

### Now (`now.html`)
Current location and activities, with images and external links

### Projects (`projects.html`)
Two-column layout showcasing recent and ongoing projects with collapsible "see more" functionality:
- Brain tumor segmentation from MRI
- Early stroke prediction with big data
- Species recognition application database (MNHN collaboration)
- Virtual reality environment for spatial audio research
- And more in the expanded view

### Art (`art.html`)
Interactive full-screen image gallery featuring photography:
- Keyboard navigation (arrow keys)
- Mouse/touch navigation (click arrows)
- Automatic image fitting to screen
- Equipment credit overlay

### Links (`links.html`)
Curated collection of external resources and social links

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, CSS variables for theming
- **JavaScript (Vanilla)** - No frameworks, lightweight interaction
- **Responsive Design** - Mobile-first CSS approach

## Design Highlights

### Color Palette
- **Background**: `#f4efe6` (Soft beige)
- **Text**: `#1f130e` (Dark brown)
- **Accent**: `#324734` (Earthy green)
- **Accent Alt**: `#7b5a3a` (Warm brown)
- **Border**: `#d9cfc2` (Subtle beige)

### Typography
System fonts for optimal performance:
```
font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
```

## Getting Started

### Local Development
1. Clone or download this repository
2. Open `index.html` in your browser
3. No build process or dependencies required

### Deployment
The site is static and can be deployed to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

Simply upload the entire directory to your server.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notable Features

### Interactive Elements
- **Animated Navigation Buttons** - Custom button-57 design with smooth transitions
- **Project Collapsing** - Expandable project lists with state management
- **Full-Screen Gallery** - Responsive image viewer with fixed navigation arrows
- **Typewriter Effect** - Intro text animation on homepage

### Photography Gallery
The art gallery (`art.html`) features 36 photographs shot on Fujifilm XT-20 with Viltrox AF 85mm f/1.8 lens, providing a professional portfolio display.

## License

This project is personal and not under a specific license. Feel free to use it as inspiration for your own portfolio.

## Author

**Tareq Derdaki**

- Website: [qer.at](https://qer.at)
- GitHub: [@TareqD5](https://github.com/TareqD5)

## Contact

For inquiries or collaborations, please reach out through the links provided on the website.

---

**Last Updated**: March 15, 2026
