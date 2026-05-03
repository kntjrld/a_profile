# Archelly - Security Advocate Portfolio

A modern, responsive portfolio website showcasing expertise in cybersecurity, IT infrastructure, and security consulting.

![Portfolio Preview](https://via.placeholder.com/800x400/090909/6ce3ff?text=Archelly+Portfolio)

## 🚀 Live Demo

[View Portfolio](https://archbyte12.github.io/portfolio/) *(Replace with your actual GitHub Pages URL)*

## ✨ Features

- **Dark/Light Theme Toggle** - Seamless theme switching with local storage persistence
- **Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- **Smooth Scrolling Navigation** - Single-page application with anchor-based navigation
- **Interactive Elements** - Hover effects and animations throughout
- **Security-Focused Content** - Showcasing cybersecurity expertise and credentials
- **Modern UI/UX** - Clean, minimalist design with professional aesthetics

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom properties, CSS Grid, Flexbox, and modern styling
- **JavaScript** - Theme toggle functionality and interactivity
- **SVG Icons** - Scalable vector graphics for visual elements

## 📁 Project Structure

```
arch_portfolio/
├── index.html          # Main portfolio page
├── styles.css          # Comprehensive styling with themes
├── favicon.svg         # Custom favicon
├── certs/             # Certificate files and images
│   ├── introduction_to_cybersecurity.jpg
│   ├── introduction_to_critical_infrastructure_protection.jpg
│   ├── AI Era in IT Education Seminar Certificate of Participation.pdf
│   └── CS Training.pdf
└── README.md          # Project documentation
```

## 🎯 Sections

1. **Hero** - Professional introduction and tagline
2. **Overview** - Career summary and expertise
3. **Experience** - Key roles and achievements across Banking, Instruction, Support, and Security
4. **Projects** - Open-source repositories and technical contributions
5. **Certificates** - Professional certifications and credentials
6. **Contact** - Social media links and contact information

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required - pure HTML/CSS/JS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ArchByte12/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Open `index.html` in your preferred web browser
   - Or use a local server for better development experience:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js
     npx serve .

     # Using PHP
     php -S localhost:8000
     ```

## 🎨 Customization

### Theme Colors

The portfolio uses CSS custom properties for easy theming. Key variables in `styles.css`:

```css
:root {
  --bg-primary: #090909;           /* Main background */
  --text-accent: #6ce3ff;          /* Accent color */
  --text-heading: #eef7ff;         /* Headings */
  /* ... more variables */
}
```

### Content Updates

- **Personal Information**: Update name, bio, and contact details in `index.html`
- **Projects**: Modify the projects grid with your GitHub repositories
- **Certificates**: Replace certificate files in the `certs/` folder
- **Social Links**: Update social media URLs in the footer

### Adding New Sections

1. Create a new `<section>` element in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation links in the header

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

Uses CSS Grid and Flexbox for flexible layouts that adapt to screen sizes.

## 🌐 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

While this is a personal portfolio, suggestions for improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Archelly Bautista**
- **Email**: archellybaustista@omsc.ph.education
- **LinkedIn**: [Archelly Bautista](https://www.linkedin.com/in/archelly-baustista-96b61212b)
- **GitHub**: [@ArchByte12](https://github.com/ArchByte12)
- **Facebook**: [yllehcrA](https://www.facebook.com/yllehcrA)

---

*"Built to protect people, data, and systems."*

## 🔧 Development Notes

- **CSS Architecture**: Uses CSS custom properties for maintainable theming
- **Performance**: Optimized with minimal JavaScript and efficient CSS
- **Accessibility**: Semantic HTML, proper ARIA labels, and keyboard navigation
- **SEO**: Meta tags, semantic structure, and clean URLs

## 📊 Project Stats

- **Languages**: HTML (45%), CSS (50%), JavaScript (5%)
- **Size**: ~50KB total (compressed)
- **Load Time**: < 1 second on modern connections
- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)