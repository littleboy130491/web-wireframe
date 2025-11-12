# Website Wireframe Project Structure Rules

## Project Organization

This repository follows a specific structure for organizing website wireframe projects:

### Main Structure
```
web-wireframe/
├── AGENTS.md
├── README.md
└── [project-folders]/
```

### Project Folder Naming Convention
- **Rule**: Use kebab-case for project folder names
- **Example**: If project name is "Perkumpulan Profesional", folder name should be `perkumpulan-profesional`
- **Pattern**: Convert spaces to hyphens, use lowercase letters

### Individual Project Structure
Each project folder should follow this structure:
```
[project-name]/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── assets/
    ├── images/
    ├── fonts/
    └── other/
```

## Technical Requirements

### HTML
- Use semantic HTML5 elements
- Keep it simple and focused on wireframe structure
- Include proper meta tags and viewport settings

### CSS
- **Preferred**: Use Tailwind CSS when possible
- Add Tailwind CDN script in the `<head>` section:
```html
<script src="https://cdn.tailwindcss.com"></script>
```
- Custom styles should go in `css/styles.css`
- Follow mobile-first responsive design

### JavaScript
- Keep scripts minimal for wireframe purposes
- Place custom JavaScript in `js/script.js`
- Use defer attribute for script tags when possible

### Assets
- **images/**: All image files (jpg, png, svg, etc.)
- **fonts/**: Custom font files if needed
- **other/**: Any additional assets (icons, videos, etc.)

## File Naming Conventions
- HTML: `index.html` (main page)
- CSS: `styles.css` (main stylesheet)
- JS: `script.js` (main JavaScript file)
- Images: Use descriptive names with kebab-case (e.g., `hero-image.jpg`)
- Fonts: Use descriptive names (e.g., `custom-font.woff2`)

## Development Guidelines
- Keep wireframes clean and focused on layout and structure
- Use placeholder content (Lorem Ipsum) where appropriate
- Ensure responsive design across different screen sizes
- Test in multiple browsers during development
- Keep file sizes minimal for fast loading
