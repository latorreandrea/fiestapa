# FiesTapa - Discover The Vibrant Flavours Of Spain

A modern, responsive single-page website for FiesTapa, a Spanish tapas catering service based in Copenhagen, Denmark. The website showcases authentic Spanish cuisine with a professional design and smooth user experience.

![FiesTapa Website](https://img.shields.io/badge/Status-Live-brightgreen) ![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue) ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.2-purple) ![Responsive](https://img.shields.io/badge/Design-Responsive-orange)

## 🌟 Live Demo

Visit the live website: [FiesTapa on GitHub Pages](https://latorreandrea.github.io/fiestapa/)

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Performance Features](#performance-features)
- [Future Enhancements](#future-enhancements)
- [Credits](#credits)
- [License](#license)

## ✨ Features

### 🎨 Design & User Experience
- **Responsive Design**: Fully responsive layout that works on all devices (mobile, tablet, desktop)
- **Spanish-Inspired Color Scheme**: Authentic color palette with gradient borders and accents
- **Smooth Animations**: Fade-in effects when sections enter the viewport using Intersection Observer API
- **Interactive Elements**: Hover effects, smooth scrolling navigation, and animated carousel
- **Professional Typography**: Montserrat Google Font with multiple weights for visual hierarchy

### 🍽️ Content Sections
- **Hero Section**: Eye-catching background image with compelling call-to-action
- **About Us**: Company introduction with event type highlights
- **Food Showcase**: Auto-rotating carousel featuring Spanish tapas
- **Know Our Tapas**: Individual tapas with descriptions and gradient-bordered images
- **Fiestapa Platter**: Special platter section with ingredient details
- **Menu Selection**: Three tier menu options (Bite, Standard, Fest)
- **Our Story**: Company mission and background narrative
- **Contact Form**: Professional contact form with validation
- **Values Section**: Core company values with icons

### 🛠️ Technical Features
- **Bootstrap 5.3.2**: Modern responsive framework
- **Vanilla JavaScript**: Clean, efficient code without heavy dependencies
- **CSS3 Animations**: Smooth transitions and effects
- **Intersection Observer**: Performance-optimized scroll animations
- **Mobile-First Design**: Optimized for mobile devices
- **SEO Friendly**: Semantic HTML structure and proper meta tags
- **Fast Loading**: Optimized images and minimal dependencies

## 🚀 Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Flexbox and Grid
- **JavaScript (ES6+)**: Modern vanilla JavaScript
- **Bootstrap 5.3.2**: Responsive framework
- **Bootstrap Icons**: Icon library

### Fonts & Assets
- **Google Fonts**: Montserrat typography
- **Custom Images**: Professional food photography
- **Gradient Borders**: CSS linear gradients for Spanish aesthetics

### Deployment
- **GitHub Pages**: Static site hosting
- **Git**: Version control

## 🏁 Getting Started

### Prerequisites
- A modern web browser
- Git (for cloning the repository)
- Code editor (VS Code recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/latorreandrea/fiestapa.git
   cd fiestapa
   ```

2. **Open the project**
   ```bash
   # Using VS Code
   code .
   
   # Or open index.html in your browser
   open index.html
   ```

3. **Local Development**
   - Open `index.html` in your browser
   - Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   ```

## 📁 Project Structure

```
fiestapa/
├── index.html              # Main HTML file
├── styles.css              # Custom CSS styles
├── script.js               # JavaScript functionality
├── README.md               # Project documentation
├── LICENSE                 # License file
└── images/                 # Image assets
    ├── logo/
    │   ├── logo.png        # Company logo
    │   └── hero_image.jpg  # Hero background
    ├── food/               # Food photography
    │   ├── food_01.jpg - food_08.jpg    # Carousel images
    │   ├── salmorejo.jpg                # Individual tapas
    │   ├── tortilla_de_patatas.jpg
    │   ├── guilda_pippara.jpg
    │   ├── olive_paste_artichoke.jpg
    │   ├── ensaladilla_olive.jpg
    │   ├── chorizo_green_pepper.jpg
    │   └── fiestapa_platter_01.jpg - fiestapa_platter_04.jpg
    └── events/             # Menu category images
        ├── fiestapa_bite.jpg
        ├── fiestapa_standar.jpg
        └── fiestapa_fest.jpg
```

## 🚀 Deployment

### GitHub Pages (Current)
The website is currently deployed on GitHub Pages, providing free static hosting with automatic deployment from the main branch.

**Deployment URL**: `https://latorreandrea.github.io/fiestapa/`

### Custom Domain Options
While the current deployment uses GitHub Pages, in a production environment, you can:

1. **Custom Domain**: Attach a custom domain (e.g., `www.fiestapa.dk`) to GitHub Pages
2. **Professional Hosting**: Deploy to services like Netlify, Vercel, or AWS S3
3. **CDN Integration**: Use CloudFlare for improved performance and security

### Server-Side Enhancement
For advanced functionality, the static site can be enhanced with:

- **Flask Framework**: Python-based server-side logic for form processing, user authentication, and dynamic content
- **Form Processing**: Server-side form validation and email sending with SMTP integration
- **Database Integration**: Customer data management with PostgreSQL or MySQL
- **Content Management**: Dynamic content updates and admin dashboard
- **Analytics**: Advanced tracking and reporting with custom backend APIs

## ⚡ Performance Features

- **Optimized Images**: Compressed images for faster loading
- **Minimal Dependencies**: Only essential libraries included
- **Efficient Animations**: Hardware-accelerated CSS transforms
- **Lazy Loading**: Intersection Observer for performance-optimized animations
- **Mobile Optimization**: Touch-friendly interface and fast mobile performance

## 🔮 Future Enhancements

### Planned Features
- **Multi-language Support**: Danish and Spanish translations
- **Online Ordering System**: Integration with payment processors
- **Customer Dashboard**: Order tracking and history
- **Admin Panel**: Content management system
- **Blog Section**: Recipe sharing and company updates
- **Social Media Integration**: Instagram feed and sharing
- **Advanced Analytics**: Customer behavior tracking

### Technical Improvements
- **Progressive Web App (PWA)**: Offline functionality
- **API Integration**: Third-party service connections
- **Database Backend**: Customer and order management
- **Email Automation**: Marketing and notification systems

## 🎯 Browser Support

- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+
- **Mobile browsers** (iOS Safari, Chrome Mobile)

## 📸 Credits

### Photography
All food photography and visual content were created and provided by **Rodrik**.
- **Portfolio**: [Rurik Foral Portfolio](https://rurikforalportfolio.my.canva.site/aboutme)
- **Role**: Professional food photographer and visual content creator
- **Contribution**: All food images, carousel photography, and visual assets used throughout the website

### Development
- **Frontend Development**: Andrea La Torre
- **Design System**: Bootstrap framework with custom Spanish-inspired styling
- **Animations**: Custom JavaScript with Intersection Observer API

### Technologies
- **Bootstrap Team**: For the responsive framework
- **Google Fonts**: Montserrat typography
- **Bootstrap Icons**: Icon library

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

**FiesTapa**
- **Email**: HELLO@FIESTAPA.DK
- **Phone**: +45 27 12 76 47
- **Instagram**: [@fiestapa.dk](https://instagram.com/fiestapa.dk)

**Developer**
- **GitHub**: [@latorreandrea](https://github.com/latorreandrea)
- **Project Link**: [https://github.com/latorreandrea/fiestapa](https://github.com/latorreandrea/fiestapa)

---

Made with ❤️ in Copenhagen | Bringing Spanish flavors to Denmark
