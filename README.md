# Professional Card Website

A modern, responsive professional card/portfolio website built with Astro. This project showcases professional information, skills, and contact details in an elegant and interactive way.

## Features

- 🚀 Built with Astro for optimal performance
- 🎨 Stylish design with gradient card and dark theme
- 📱 Fully responsive layout
- 🗂️ Projects showcase page
- 🔧 Customizable content through JSON data files
- 🎯 SEO optimized
- 💎 Elegant glassmorphism design effects

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
│   └── favicon.ico
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

This project is licensed under the MIT License.
