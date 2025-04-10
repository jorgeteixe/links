# 🔗 jorgeteixe's links @ links.teixe.es

A modern, clean, and responsive personal links page built with Astro. This project serves as a centralized hub for your online presence, featuring your social media profiles and other content.

## Features

- 🎨 Clean and modern design
- 📱 Fully responsive
- ⚡ Built with Astro for optimal performance
- 🎯 Easy to customize and extend
- 🔗 Social media integration
- 🖼️ Profile image support
- 🎭 Placeholder sections for future content

## Tech Stack

- [Astro](https://astro.build) - Modern static site builder
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [Astro Icon](https://github.com/natemoo-re/astro-icon) - Icon integration

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jorgeteixe/links.git
cd links
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:4321`

## Customization

### Profile Information

Edit the following in `src/pages/index.astro`:
- Profile image URL
- Name
- Bio text
- Social media links

### Social Links

Add or modify social links in the `socialLinks` array in `src/pages/index.astro`:

```javascript
const socialLinks = [
  {
    name: 'Platform Name',
    icon: 'icon-name',
    url: 'https://your-profile-url',
  },
  // Add more links as needed
];
```

### Icons

This project uses Astro Icon with Material Design Icons and custom social icons. You can find available icons at:
- [Material Design Icons](https://pictogrammers.com/library/mdi/)
- Custom social icons are located in `src/icons/social/`

## Deployment

This project can be deployed to any static hosting service. Some popular options:

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [GitHub Pages](https://pages.github.com)

## License

This project is open source and available under the [GPL-3.0](LICENSE).
© 2025 Jorge Teixeira. All rights reserved.