![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)

# Trillo

An all-in-one booking app with a modern UI design. This project showcases advanced CSS techniques and responsive design patterns.

## Features

- Responsive layout for all screen sizes
- Modern CSS animations and transitions
- SASS/SCSS architecture with modular structure
- CSS custom properties for theming
- SVG icons with mask functionality

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm

### Installation

```bash
npm install
```

### Development

Start the development server with live reload:

```bash
npm start
```

This will run:
- Live server on `http://127.0.0.1:8080`
- SASS watcher for CSS compilation

### Build

Compile and optimize CSS for production:

```bash
npm run build:css
```

### Format Code

Format all files with Prettier:

```bash
npm run format
```

## Project Structure

```
├── css/
│   └── style.css          # Compiled CSS
├── img/
│   ├── SVG/               # SVG icons
│   └── *.jpg              # Images
├── sass/
│   ├── _base.scss         # Base styles
│   ├── _components.scss   # Component styles
│   ├── _layout.scss       # Layout styles
│   └── main.scss          # Main SASS file
├── index.html
└── package.json
```

## Author

Beni Candra

## License

ISC
