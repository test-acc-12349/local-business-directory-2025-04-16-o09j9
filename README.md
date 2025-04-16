# Local Business Directory

> Discover the best local businesses in one place - A modern, responsive directory website with a clean 3-column grid layout.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
  - [Directory Items](#directory-items)
  - [Categories](#categories)
  - [Hero Section](#hero-section)
  - [Styling](#styling)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Support](#support)

## Overview

Local Business Directory is a modern directory website template designed to showcase local businesses in an organized, searchable format. Built with HTML5, CSS3, and JavaScript, it features a responsive design that works seamlessly across all devices.

## Features

- Responsive 3-column grid layout
- Category-based filtering
- Search functionality
- Business detail pages
- Contact forms
- Mobile-friendly design
- SEO optimized
- Fast loading performance
- Custom category labels
- Social media integration

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Basic knowledge of HTML/CSS

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/local-business-directory.git

# Navigate to project directory
cd local-business-directory

# Install dependencies
npm install

# Start development server
npm start
```

## Directory Structure

```
local-business-directory/
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
├── data/
│   └── businesses.json
├── pages/
├── index.html
├── README.md
└── package.json
```

## Customization

### Directory Items

To add or edit business listings, modify the `data/businesses.json` file:

```json
{
  "businesses": [
    {
      "id": "1",
      "name": "Business Name",
      "category": "Restaurant",
      "address": "123 Main St",
      "phone": "(555) 123-4567",
      "website": "https://example.com",
      "image": "assets/images/business1.jpg"
    }
  ]
}
```

### Categories

Edit category labels in `assets/js/categories.js`:

```javascript
const categories = [
  "Restaurant",
  "Retail",
  "Services",
  "Entertainment"
];
```

### Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your Custom Heading</h1>
  <p>Your custom description text</p>
</section>
```

### Styling

Customize colors and styles in `assets/css/variables.css`:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  --text-color: #333333;
}
```

## Deployment

1. Build the project:
```bash
npm run build
```

2. Deploy to your hosting service:
```bash
npm run deploy
```

## Custom Domain Setup

1. Purchase a domain from your preferred registrar
2. Add DNS records:
   - A Record: Point to your hosting IP
   - CNAME Record: www to your domain

3. Update domain settings in your hosting panel
4. Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues

1. Images not loading
   - Check file paths
   - Verify image formats
   - Ensure proper permissions

2. Layout breaks
   - Clear browser cache
   - Check CSS media queries
   - Validate HTML structure

3. Search not working
   - Verify JavaScript console
   - Check data structure
   - Confirm API endpoints

## Resources

- [Documentation](https://docs.example.com)
- [Video Tutorials](https://youtube.com/example)
- [API Reference](https://api.example.com)
- [Style Guide](https://style.example.com)

## Support

- Create an issue in the GitHub repository
- Email support: support@example.com
- Join our [Discord community](https://discord.gg/example)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name](https://github.com/yourusername)