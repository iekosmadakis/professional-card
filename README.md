# Professional Card Website

A modern, responsive professional card/portfolio website built with Astro. This project showcases professional information, skills, and contact details in an elegant and interactive way.

## Features

- 🚀 Built with Astro for optimal performance
- 🎨 Stylish design with gradient card and dark theme
- 📱 Fully responsive layout across all devices
- 🗂️ Projects showcase page
- 🖥️ Self-hosted projects gallery
- 🔧 Customizable content through JSON data files
- 🎯 Comprehensive SEO optimization
- 💎 Elegant translucent card surfaces
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
│   │   ├── Projects.astro
│   │   └── SelfHostedProjects.astro
│   ├── data/
│   │   ├── aboutMe.json
│   │   ├── projects.json
│   │   └── selfHostedProjects.json
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── projects.astro
│   │   └── self-hosted.astro
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
- **Self-Hosted (/self-hosted)** - Gallery of self-hosted open-source projects running on personal infrastructure

## Customization

To customize the content:

1. **Personal Information**: Edit `src/data/aboutMe.json`
2. **Projects**: Update `src/data/projects.json`
3. **Self-Hosted Projects**: Update `src/data/selfHostedProjects.json`
4. **Profile Image**: Replace `public/images/profile.webp`
5. **Styling**: Modify CSS files in `src/styles/`

## Development

The project uses Astro's static site generation capabilities with TypeScript for type safety. The styling is handled through custom CSS with modern features like gradients, backdrop filters, and smooth animations.

## License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.

Copyright (c) 2026 Ioannis E. Kosmadakis

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
