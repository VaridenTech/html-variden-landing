# Variden Tech Landing Page

A modern, responsive landing page for Variden Tech IT solutions company. This project uses HTML, SCSS, and JavaScript to create a professional and engaging web presence.

![Variden Tech](assets/img/logos/Mediamodifier-Design-Template-tiny.png)

## Features

- Responsive design that works on all devices
- Modern and clean UI with smooth animations
- Client showcase section
- Team member profiles
- Service offerings display
- Optimized for performance with minified CSS and JS

## Setup and Installation

### Prerequisites

- Node.js (v14 or later recommended)
- npm or yarn

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd html-variden-landing
   ```

2. Install dependencies:
   ```
   npm install
   ```

### Development

To run the project in development mode with automatic SCSS compilation:

```
npm run dev
```

This will:

- Watch for changes in SCSS files and recompile them
- Build the JavaScript files

## Build Process

### CSS Compilation

The project uses SCSS for styling which is compiled and minified into a single CSS file:

```
npm run scss
```

This command compiles `assets/scss/style.scss` into `assets/css/style.min.css` with compression.

### JavaScript Minification

JavaScript files are combined and minified using uglify-js:

```
npm run js
```

This command minifies the following JS files into a single `scripts.min.js` file:

- viewport.jquery.js
- jquery.waypoints.js
- main.js
- ajax-mail.js

### Complete Build

To build both CSS and JS at once:

```
npm run build
```

## Project Structure

```
html-variden-landing/
├── assets/
│   ├── css/           # Compiled CSS files
│   ├── js/            # JavaScript files
│   ├── img/           # Images and icons
│   │   └── clients/   # Client logo images
│   └── scss/          # SCSS source files
├── index.html         # Main landing page
├── favicon.ico        # Favicon
└── site.webmanifest   # Web app manifest
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Contact

Variden Tech - [contact@varidentech.com](mailto:contact@varidentech.com)

Project Link: [https://github.com/your-username/html-variden-landing](https://github.com/your-username/html-variden-landing)
