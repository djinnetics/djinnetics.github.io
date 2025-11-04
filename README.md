# Djinnetics - AI-Powered Personal Trainer Website

A modern, responsive, and animated static website showcasing the **Djinnetics** mobile fitness app — an AI-powered
personal trainer with personalized workouts and real-time tracking.

## 🚀 Features

- **Modern Design**: Clean, minimal layout with gradient animations and smooth transitions
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Scroll Animations**: Intersection Observer API for smooth scroll-triggered animations
- **Interactive Effects**:
    - Parallax scrolling on hero section
    - 3D tilt effects on hover
    - Floating particles and gradient orbs
    - Button ripple effects
    - Pulsing CTA animations
- **Performance Optimized**:
    - CSS-based animations for better performance
    - Lazy loading support
    - Respects user's reduced motion preferences
    - Lightweight and fast loading

## 📁 Project Structure

```
DjinneticsWebsite/
├── index.html          # Main HTML file with semantic structure
├── style.css           # Complete CSS with animations and responsive design
├── script.js           # JavaScript for scroll animations and interactions
├── assets/             # Directory for images and screenshots
│   ├── screenshot_hero.png
│   ├── feature1.png
│   ├── feature2.png
│   ├── feature3.png
│   └── feature4.png
└── README.md           # This file
```

## 🎨 Design Specifications

### Color Palette

- **Primary Blue**: `#3B82F6`
- **Secondary Green**: `#10B981`
- **Text Color**: `#1F2937`
- **Background**: `#ffffff`

### Typography

- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800

### Sections

1. **Hero Section**: Full-screen with gradient background, animated particles, and app preview
2. **Features Section**: Four alternating feature blocks with app screenshots
3. **CTA Section**: Call-to-action with animated gradient background
4. **Footer**: Links and copyright information

## 🖼️ Adding Your Screenshots

To complete the website, add your app screenshots to the `assets/` folder:

1. `screenshot_hero.png` - Main app screenshot for hero section (recommended: 1080x2340px)
2. `feature1.png` - Personalized workouts screen
3. `feature2.png` - Workout library screen
4. `feature3.png` - Tracking screen
5. `feature4.png` - AI coach chat screen

**Note**: The website includes fallback placeholder images (SVG) if screenshots are missing, so it will display
correctly even without the actual images.

## 🌐 Deployment

### Option 1: Static Hosting (Recommended)

Deploy to any static hosting service:

- **Netlify**: Drag and drop the entire folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Push to a repository and enable Pages
- **Cloudflare Pages**: Direct upload or Git integration

### Option 2: Local Development

Simply open `index.html` in any modern web browser:

```bash
# Option A: Double-click index.html
# Option B: Use a local server
python3 -m http.server 8000
# or
npx serve
```

Then visit `http://localhost:8000` in your browser.

## 🎭 Animations & Interactions

### Scroll Animations

- Hero section elements fade in sequentially on load
- Feature sections slide in from left/right when scrolled into view
- Footer fades in from bottom
- Smooth scroll behavior for navigation links

### Interactive Effects

- **Navigation**: Sticky header with fade background on scroll
- **Hero**: Parallax effect and floating particles
- **Features**: 3D tilt effect on phone mockups
- **Buttons**: Hover scaling and ripple click effect
- **CTA**: Continuous pulse animation on download buttons

## 🔧 Customization

### Update Content

Edit `index.html` to change:

- App name and taglines
- Feature titles and descriptions
- App Store and Google Play links (replace `#` with actual URLs)
- Footer links

### Modify Colors

Edit CSS custom properties in `style.css`:

```css
:root {
    --color-primary: #3B82F6;    /* Change primary color */
    --color-secondary: #10B981;   /* Change secondary color */
    --color-text: #1F2937;        /* Change text color */
}
```

### Adjust Animations

Modify animation speeds in `style.css`:

```css
:root {
    --transition-fast: 0.2s ease;
    --transition-base: 0.3s ease;
    --transition-slow: 0.6s ease;
}
```

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: > 968px (full two-column layout)
- **Tablet**: 640px - 968px (single column, adjusted spacing)
- **Mobile**: < 640px (stacked layout, full-width buttons)

## 🚦 Performance Tips

1. **Optimize Images**: Compress screenshots before adding to assets folder
2. **Use WebP Format**: Convert PNG images to WebP for better compression
3. **CDN Delivery**: Host assets on a CDN for faster global delivery
4. **Minify Files**: Use tools like CSS Minifier and JS Minifier for production

## 📄 License

© 2025 Djinnetics. All rights reserved.

## 🤝 Contributing

This is a static website template. Feel free to customize and adapt for your needs!

## 📞 Support

For questions or support, update the footer contact links in `index.html`.

---

**Built with ❤️ using HTML, CSS, and vanilla JavaScript**
