# 3D Web Anime

A modern, interactive 3D gaming-themed web experience built with React and GSAP. This project showcases advanced web animations, video integration, and responsive design with a gaming aesthetic inspired by anime culture.

🌐 **Live Demo**: [3d-web-anime.vercel.app](https://3d-web-anime.vercel.app)

## ✨ Features

- **Interactive 3D Animations**: Powered by GSAP (GreenSock Animation Platform) with scroll-triggered effects
- **Dynamic Video Backgrounds**: Seamless video switching with custom controls and loading states
- **Gaming-Themed UI**: Anime-inspired design with modern gaming aesthetics
- **Responsive Design**: Fully responsive layout optimized for all devices
- **Smooth Scroll Effects**: Advanced scroll-triggered animations and transitions
- **Component-Based Architecture**: Modular React components for scalability
- **Modern Build Tools**: Lightning-fast development with Vite

## 🛠️ Tech Stack

### Frontend
- **React** (18.3.1) - Component-based UI library
- **GSAP** (3.12.5) - Professional animation library
- **@gsap/react** (2.1.1) - React integration for GSAP
- **Tailwind CSS** (3.4.14) - Utility-first CSS framework
- **React Icons** (5.3.0) - Icon library
- **React Use** (17.5.1) - Essential React hooks

### Development Tools
- **Vite** (5.4.10) - Next-generation build tool
- **ESLint** (9.14.0) - Code linting and quality
- **Prettier** (3.3.3) - Code formatting
- **PostCSS** (8.4.49) - CSS processing
- **Autoprefixer** (10.4.20) - CSS vendor prefixes

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/laladwesh/3d-web-anime.git
   cd 3d-web-anime
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Visit `http://localhost:5173` to view the project

### Available Scripts

```bash
npm run dev     # Start development server
npm run build   # Build for production
npm run preview # Preview production build
npm run lint    # Run ESLint
```

## 📁 Project Structure

```
3d-web-anime/
├── public/
│   ├── audio/          # Audio assets
│   ├── fonts/          # Custom fonts
│   ├── img/            # Image assets
│   ├── videos/         # Video backgrounds
│   └── vite.svg
├── src/
│   ├── assets/         # React assets
│   ├── components/     # React components
│   │   ├── About.jsx
│   │   ├── AnimatedTitle.jsx
│   │   ├── Button.jsx
│   │   ├── Contact.jsx
│   │   ├── Features.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   ├── Story.jsx
│   │   └── VideoPreview.jsx
│   ├── App.jsx         # Main application component
│   ├── index.css       # Global styles
│   └── main.jsx        # Application entry point
├── index.html          # HTML template
├── package.json        # Dependencies and scripts
├── tailwind.config.js  # Tailwind configuration
├── vite.config.js      # Vite configuration
└── README.md
```

## 🎯 Key Components

### Hero Section
- Interactive video background with switching functionality
- GSAP-powered animations and scroll triggers
- Gaming-themed messaging and call-to-action buttons
- Loading states and video optimization

### Navigation
- Responsive navigation bar
- Smooth scroll navigation between sections
- Mobile-friendly hamburger menu

### Features Section
- Showcase of key project features
- Animated elements with scroll triggers
- Gaming-inspired visual design

### Story Section
- Narrative content with engaging animations
- Video integration and interactive elements

### Contact Section
- Contact form with modern styling
- Social media integration
- Responsive design elements

## 🎨 Design Philosophy

This project combines:
- **Anime Aesthetics**: Visual elements inspired by anime and gaming culture
- **Modern Web Standards**: Latest React patterns and performance optimizations
- **Immersive Experience**: 3D effects and smooth animations for engagement
- **Gaming Theme**: UI/UX designed for gaming community appeal

## 🔧 Customization

### Adding New Animations
The project uses GSAP for animations. To add new effects:

```javascript
import gsap from "gsap";
import { useGSAP } from "@gsap/react";

useGSAP(() => {
  gsap.from(".my-element", {
    y: 100,
    opacity: 0,
    duration: 1,
    scrollTrigger: {
      trigger: ".my-element",
      start: "top 80%",
    }
  });
});
```

### Styling with Tailwind
The project uses Tailwind CSS for styling. Customize the design by:
- Modifying `tailwind.config.js`
- Using Tailwind utility classes
- Adding custom CSS in `index.css`

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **GSAP Team** - For the amazing animation library
- **React Team** - For the excellent frontend framework
- **Tailwind CSS** - For the utility-first CSS framework
- **Anime Community** - For inspiration and aesthetic guidance

## 📞 Contact

- **GitHub**: [@laladwesh](https://github.com/laladwesh) and [@sherosomu](https://github.com/sherosomu)
- **Live Demo**: [3d-web-anime.vercel.app](https://3d-web-anime.vercel.app)

---

Built with ❤️ by @laladwesh and @sherosomu
