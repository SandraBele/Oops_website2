# Oops Website - Professional Pregnancy Tests B2B Platform

A modern, responsive B2B e-commerce website for wholesale pregnancy test distribution.

## Features

- **Modern Design**: Dark theme with pink accents and glassmorphism effects
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **B2B Authentication**: Wholesaler login system with bulk pricing
- **Product Catalog**: Three main products with detailed specifications
- **Shopping Cart**: Bulk discount calculations and order management
- **Public Access**: Site content accessible without login, pricing gated behind authentication

## Quick Start

1. Clone or download this repository
2. Open `index.html` in a web browser
3. For local development, serve with a simple HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
4. Visit `http://localhost:8000`

## File Structure

```
├── index.html          # Homepage with hero section and company info
├── products.html       # Product catalog with detailed specifications
├── login.html          # Wholesaler authentication
├── signup.html         # Wholesaler registration
├── cart.html           # Shopping cart and checkout
├── styles.css          # Main stylesheet with modern design
├── script.js           # JavaScript functionality and authentication
├── images/             # Product images
│   ├── midstream-product.jpg
│   ├── cassette-product.jpg
│   └── weekly-product.jpg
└── *.jpg              # Hero and background images
```

## Authentication System

- **Public Access**: All pages and product information accessible without login
- **Pricing Gated**: Product prices and bulk discounts only visible after wholesaler login
- **Demo Credentials**: Use any email/password combination for testing (client-side demo)

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Optimized responsive design

## Development Notes

- Uses vanilla HTML5, CSS3, and JavaScript
- No external dependencies or frameworks
- Client-side data storage with localStorage
- Responsive design with mobile-first approach
- Modern CSS features (Grid, Flexbox, Custom Properties)

## Contact

For questions or support, contact the development team.
