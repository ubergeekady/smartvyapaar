# SmartVyapaar Landing Page

A modern, responsive landing page for SmartVyapaar - India's Complete Business Automation Solution. Built with HTML, Tailwind CSS, and optimized for production deployment.

## 🚀 Quick Start

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd smartvyapaar
```

2. Install dependencies:
```bash
npm install
```

## 🛠️ Development

### Development Mode

To start development with CSS watching:

```bash
npm run dev
```

This will:
- Watch for changes in Tailwind CSS files
- Automatically rebuild CSS when changes are detected
- Output compiled CSS to `css/main.css`

### Available Scripts

- `npm run dev` - Start development mode with CSS watching
- `npm run build:css` - Build CSS for development
- `npm run watch:css` - Watch CSS files for changes
- `npm run build` - Build production-ready files
- `npm run serve` - Serve the built files locally
- `npm run clean` - Clean the dist directory

## 📦 Production Build

To create a production build:

```bash
npm run build
```

This will:
1. Clean the `dist` directory
2. Create necessary directories
3. Build and minify CSS with Tailwind CSS
4. Copy HTML files to `dist/`
5. Copy public assets (favicon, manifest, etc.) to `dist/`

The production files will be available in the `dist/` folder, ready for deployment.

## 🌐 Local Preview

To preview the production build locally:

```bash
npm run serve
```

This will start a local server at `http://localhost:8080` and automatically open it in your browser.

## 📁 Project Structure

```
smartvyapaar/
├── css/
│   ├── main.css          # Compiled Tailwind CSS (generated)
│   └── tailwind.css      # Tailwind CSS source
├── public/
│   ├── favicon.ico       # Website favicon
│   └── manifest.json     # Web app manifest
├── dist/                 # Production build output (generated)
│   ├── css/
│   │   └── main.css      # Minified CSS
│   ├── index.html        # Production HTML
│   ├── favicon.ico       # Copied favicon
│   └── manifest.json     # Copied manifest
├── index.html            # Main HTML file
├── package.json          # Dependencies and scripts
├── tailwind.config.js    # Tailwind CSS configuration
└── README.md            # This file
```

## 🎨 Styling

This project uses Tailwind CSS for styling with a custom configuration that includes:

- Custom color palette for SmartVyapaar branding
- Extended font families (Inter, Open Sans, Poppins)
- Custom animations and transitions
- Responsive design utilities
- Additional Tailwind plugins for enhanced functionality

### Key Features

- **Responsive Design**: Mobile-first approach with breakpoint-specific styles
- **Custom Color System**: Brand-consistent color palette
- **Typography**: Multiple font families for different content types
- **Animations**: Smooth transitions and hover effects
- **Component-based**: Reusable utility classes

## 🚀 Deployment

### Static Hosting (Recommended)

The `dist/` folder contains all the files needed for deployment. You can deploy to any static hosting service:

#### Netlify
1. Build the project: `npm run build`
2. Drag and drop the `dist/` folder to Netlify
3. Or connect your Git repository and set build command to `npm run build` and publish directory to `dist`

#### Vercel
1. Build the project: `npm run build`
2. Deploy the `dist/` folder using Vercel CLI or web interface

#### GitHub Pages
1. Build the project: `npm run build`
2. Copy contents of `dist/` to your GitHub Pages repository
3. Or use GitHub Actions to automate the build and deploy process

#### Traditional Web Hosting
1. Build the project: `npm run build`
2. Upload the contents of the `dist/` folder to your web server's public directory

### Build Optimization

The production build includes:
- **Minified CSS**: Tailwind CSS is purged and minified for optimal file size
- **Optimized HTML**: Clean, production-ready HTML
- **Asset Optimization**: All assets are copied and organized for deployment
- **Cache-friendly**: Static files can be cached by CDNs and browsers

## 🔧 Customization

### Modifying Styles

1. Edit `css/tailwind.css` for global styles
2. Modify `tailwind.config.js` for theme customization
3. Update HTML classes directly in `index.html`
4. Run `npm run dev` to see changes in real-time

### Adding New Pages

1. Create new HTML files in the root directory
2. Update the build scripts in `package.json` to copy new files
3. Ensure proper linking between pages

### Custom Components

The project uses Tailwind CSS utility classes. For complex components:
1. Create reusable class combinations
2. Use Tailwind's `@apply` directive in `css/tailwind.css`
3. Follow the existing design system

## 📱 Browser Support

This project supports all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test the build: `npm run build`
5. Commit your changes: `git commit -m 'Add feature'`
6. Push to the branch: `git push origin feature-name`
7. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support and questions:
- Create an issue in the repository
- Contact the development team
- Check the documentation for common solutions

---

Built with ❤️ for SmartVyapaar
