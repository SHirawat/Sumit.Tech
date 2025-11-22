# Sumit.Tech - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my work as a Web Developer and Designer. Built with a sleek dark theme and smooth animations.

## 🌟 Features

- **Modern Design**: Dark theme with sky blue accents and glassmorphism effects
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and fade-in effects
- **Loading Screen**: Elegant loading animation on page load
- **Interactive Navigation**: Fixed navbar with smooth scrolling and mobile menu
- **Project Showcase**: Display of multiple projects with links to GitHub, Figma, and live demos
- **Skills Section**: Visual representation of technical skills and tools
- **Contact Section**: Easy-to-use contact form with social media links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles and animations
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons library
- **Google Fonts**: Inter font family

## 📁 Project Structure

```
Sumit Website/
├── index.html              # Main HTML file
├── assets/
│   └── images/
│       └── WhatsApp Image 2025-08-05 at 22.16.45_43f581a9.jpg  # Profile image
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or package managers required - the site uses CDN resources

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd "Sumit Website"
   ```

2. Open `index.html` in your web browser:
   - Simply double-click the file, or
   - Use a local server (recommended for development):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. Navigate to `http://localhost:8000` in your browser

## 📝 Customization

All personal information and content can be customized in the JavaScript section of `index.html`:

### Personal Data Configuration

Edit the `personalData` object (around line 410) to update:

- **Name**: Your full name
- **Email**: Your contact email
- **Skills**: Add or remove skills with icons and colors
- **Projects**: Update project details, links, and descriptions

```javascript
const personalData = {
    name: "Your Name",
    email: "your.email@example.com",
    skills: [
        { name: "Skill Name", icon: "fab fa-icon-class", color: "text-color-class" }
    ],
    projects: [
        {
            title: "Project Title",
            description: "Project description",
            tech: ["Tech1", "Tech2"],
            github: "https://github.com/...",
            live: "https://live-demo.com"
        }
    ]
};
```

### Styling

- **Colors**: Modify the Tailwind config section (around line 15) to change the color scheme
- **Fonts**: Update the Google Fonts link to use different fonts
- **Animations**: Adjust animation timings and effects in the CSS section

## 🎨 Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal background and story
3. **Skills Section**: Technical skills and tools grid
4. **Projects Section**: Portfolio of featured projects
5. **Contact Section**: Contact information and social links
6. **Footer**: Additional links and copyright information

## 🔗 Social Links

- **GitHub**: [@SHirawat](https://github.com/SHirawat)
- **LinkedIn**: [Sumit Hirawat](https://www.linkedin.com/in/sumit-hirawat-71a335276/)
- **Instagram**: [@hirawat_sumit](https://www.instagram.com/hirawat_sumit/)
- **Email**: sumit@hirawat.in

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎯 Key Features Explained

### Scroll Animations
The website uses Intersection Observer API to trigger animations when sections come into view. Multiple animation types are available:
- Fade in
- Slide left/right/up
- Scale
- Rotate

### Mobile Menu
Responsive hamburger menu that toggles on mobile devices for easy navigation.

### Loading Screen
Animated loading screen that displays on initial page load for a polished user experience.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Sumit Hirawat**
- Website: [Sumit.Tech](https://sumit.tech)
- Email: sumit@hirawat.in

## 🙏 Acknowledgments

- Tailwind CSS for the utility-first CSS framework
- Font Awesome for the icon library
- Google Fonts for the Inter font family

---

Built with ❤️ by Sumit Hirawat

