# Project Structure & Organization

## File Structure
```
Sumit Website/
├── index.html              # Main HTML file (single-page application)
├── assets/
│   └── images/
│       └── *.jpg           # Profile and project images
├── .kiro/
│   ├── specs/              # Feature specifications
│   └── steering/           # AI assistant guidance rules
├── .git/                   # Git repository
├── .vscode/                # VS Code settings
└── README.md              # Project documentation
```

## Code Architecture

### HTML Structure (index.html)
- **Head Section**: Meta tags, CDN links, Tailwind config, custom CSS
- **Body Sections**: 
  - Loading screen
  - Fixed navigation
  - Hero section
  - About section (#about)
  - Skills section (#skills) 
  - Projects section (#projects)
  - Contact section (#contact)
  - Footer
  - JavaScript logic

### CSS Organization
- **Tailwind Config**: Custom theme colors, fonts, animations
- **Custom CSS**: Scrollbar, glass effects, loading animations, scroll reveals
- **Responsive Design**: Mobile-first approach with breakpoints

### JavaScript Structure
- **Configuration**: `personalData` object for easy content updates
- **Render Functions**: Dynamic content generation for skills/projects
- **Interactivity**: Mobile menu, scroll effects, animations
- **Utilities**: Toast notifications, scroll observers

## Content Management
- **Personal Data**: Centralized in `personalData` JavaScript object
- **Skills**: Array of objects with name, icon, color
- **Projects**: Array with title, description, tech stack, links
- **Contact Info**: Email, social media links

## Asset Organization
- **Images**: Stored in `assets/images/` directory
- **Icons**: Font Awesome classes and Devicon CDN links
- **Fonts**: Google Fonts (Inter family)

## Development Workflow
1. Edit `personalData` object for content changes
2. Modify CSS variables for styling updates
3. Test locally with simple HTTP server
4. Deploy static files to hosting platform

## Naming Conventions
- **CSS Classes**: Tailwind utilities + custom classes with kebab-case
- **JavaScript**: camelCase for variables and functions
- **IDs**: kebab-case for HTML element IDs
- **Files**: kebab-case for file names