# Nexter – Real Estate Landing Page

A modern and responsive real estate landing page built with **HTML**, **SCSS**, and **CSS Grid**. Inspired by Jonas Schmedtmann's advanced CSS course.

## 💡 Features

- Fully responsive layout using CSS Grid
- Mobile-first design
- Custom icon system with SVG sprites
- Sass architecture (7-1 pattern)
- Modular SCSS partials
- Clean and modern UI
- Simple build process with Sass CLI

## 📸 Preview

![Nexter Screenshot](img/house-1.jpeg)

## 🧱 Tech Stack

- HTML5
- Sass (SCSS)
- CSS Grid & Flexbox
- Google Fonts
- SVG Sprites

## 📁 Folder Structure

```bash
NEXTER/
├── css/                 # Compiled CSS
├── img/                 # Images and icons
├── node_modules/        # NPM packages
├── sass/
│   ├── base/            # SCSS partials (variables, base, components)
│   └── main.scss        # Entry point for all SCSS
├── index.html           # Main HTML file
├── package.json         # NPM scripts and metadata
├── README.md            # You're here
└── .gitignore           # Files to ignore in version control
```

## 🛠️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/your-username/nexter.git
cd nexter

# Install dependencies
npm install

# Start Sass watcher
npm run start

```

📝 Scripts

"scripts": {
"start": "sass --load-path=sass sass/main.scss css/style.css --watch"
}

🙌 Credits
This project is based on the design by Jonas Schmedtmann.

📄 License
Free to use for personal or learning purposes.
Not for resale or course redistribution.

NOTE: ⚙️ Sass Compiler
This project uses Dart Sass, not the older Node-sass (LibSass) version originally used by Jonas Schmedtmann.

Why Dart Sass?
✅ Officially Supported: Dart Sass is the primary implementation of Sass and is actively maintained by the Sass team.

🚫 LibSass is Deprecated: Node-sass (which Jonas used) is based on LibSass, which has been officially deprecated and no longer receives updates.

🧰 Modern Features: Dart Sass supports newer features like the @use and @forward rules, ensuring your project is future-proof.

🌐 Cross-platform: Dart Sass runs on all major operating systems without the native dependency issues Node-sass often has.
