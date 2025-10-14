# Professional Card Website

A modern, responsive professional card/portfolio website built with Astro. This project showcases professional information, skills, and contact details in an elegant and interactive way.

## Features

- 🚀 Built with Astro for optimal performance
- 🎨 Stylish design with gradient card and dark theme
- 📱 Fully responsive layout across all devices
- 🗂️ Projects showcase page
- 🔧 Customizable content through JSON data files
- 🎯 Comprehensive SEO optimization
- 💎 Elegant glassmorphism design effects
- ♿ Enhanced accessibility with ARIA labels

## Installation

```bash
# Clone the repository
git clone https://github.com/iekosmadakis/professional-card.git

# Navigate to project directory
cd professional-card

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Technologies Used

- **Astro** - Static site generator
- **TypeScript** - Type-safe JavaScript
- **CSS3** - Custom styling with modern features
- **Bootstrap Icons** - Icon library
- **Google Fonts (Lato)** - Typography

## Project Structure

```
professional-card/
├── public/
│   ├── images/
│   │   └── profile.webp
│   ├── favicon.ico
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── components/
│   │   ├── Card.astro
│   │   └── Projects.astro
│   ├── data/
│   │   ├── aboutMe.json
│   │   └── projects.json
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   └── projects.astro
│   └── styles/
│       ├── global.css
│       ├── card.css
│       └── projects.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Pages

- **Home (/)** - Main professional card with personal information and social links
- **Projects (/projects)** - Showcase of featured projects with live demos and GitHub links

## Customization

To customize the content:

1. **Personal Information**: Edit `src/data/aboutMe.json`
2. **Projects**: Update `src/data/projects.json` 
3. **Profile Image**: Replace `public/images/profile.webp`
4. **Styling**: Modify CSS files in `src/styles/`

## Development

The project uses Astro's static site generation capabilities with TypeScript for type safety. The styling is handled through custom CSS with modern features like gradients, backdrop filters, and smooth animations.

## License

MIT License

Copyright (c) 2025 Ioannis E. Kosmadakis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
