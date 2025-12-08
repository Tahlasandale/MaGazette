# AGENTS.md

## Build/Lint/Test Commands
- No build system - static HTML/CSS/JS files
- No linting tools configured
- No testing framework - manual testing only

## Code Style Guidelines

### HTML
- Use semantic HTML5 elements
- Set `lang="fr"` for French content
- Include proper meta tags (charset, viewport)

### CSS
- Inline styles in `<style>` tags
- Use modern CSS: flexbox, grid, clip-path
- Class naming: kebab-case (e.g., `app-card`, `goal-item`)
- Responsive design with media queries
- No CSS variables or preprocessors

### JavaScript
- ES6+ syntax: arrow functions, template literals, async/await
- camelCase for variables/functions (e.g., `updateClock`, `getWeather`)
- Use `localStorage` for data persistence
- Error handling: try/catch blocks
- DOM manipulation: `document.getElementById()`, `querySelectorAll()`
- Event listeners: `addEventListener()`
- No external dependencies except CDN scripts (e.g., marked.js)

### General
- No TypeScript or type checking
- No package management (no package.json)
- French language comments and strings
- Accessibility: basic semantic HTML, no ARIA attributes