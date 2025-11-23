# Technology Stack & Build System

## Core Technologies
- **HTML5**: Semantic markup with modern standards
- **CSS3**: Custom styles with advanced features (flexbox, grid, animations)
- **Vanilla JavaScript**: No frameworks, pure ES6+ JavaScript
- **Tailwind CSS**: Utility-first CSS framework (loaded via CDN)

## External Dependencies (CDN)
- **Tailwind CSS**: `https://cdn.tailwindcss.com`
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`
- **Google Fonts**: Inter font family
- **Devicons**: For skill icons (`https://cdn.jsdelivr.net/gh/devicons/devicon/`)

## Build System
- **No build process required** - static HTML site
- All dependencies loaded via CDN
- No package.json or build tools needed

## Development Commands
```bash
# Local development server (Python)
python -m http.server 8000

# Alternative with Node.js
npx http-server

# Access at http://localhost:8000
```

## Browser Support
- Chrome (latest)
- Firefox (latest) 
- Safari (latest)
- Edge (latest)

## Performance Considerations
- CDN-based dependencies for fast loading
- Optimized images in WebP format when possible
- Minimal JavaScript for fast execution
- CSS animations using transform/opacity for GPU acceleration

## Code Organization
- Single HTML file with embedded CSS and JavaScript
- Inline Tailwind configuration for custom theme
- Modular JavaScript sections for different features
- Personal data configuration object for easy customization