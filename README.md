# Automatifan.rs - Native HTML/CSS Web App

Native web application converted from WordPress site. This is a static HTML/CSS website for a vending machine business (automati za kafu - coffee machines).

## Project Structure

```
fan-web/
├── index.html          # Homepage
├── products.html       # Products page
├── contact.html        # Contact page
├── css/
│   └── style.css      # Main stylesheet with design system
├── js/
│   └── main.js        # JavaScript for interactions
├── images/            # Image assets
├── PROJECT_ANALYSIS.md # Detailed project analysis
└── README.md          # This file
```

## How to Run the Website

### Option 1: Simple File Opening (Quick Test)
Simply open `index.html` in your web browser:
- Double-click `index.html` in your file explorer
- Or right-click → "Open with" → Choose your browser

**Note:** Some features (like smooth scrolling, certain CSS features) may work better with a local server.

### Option 2: Python HTTP Server (Recommended)
If you have Python installed:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and go to: `http://localhost:8000`

### Option 3: Node.js HTTP Server
If you have Node.js installed:

```bash
# Install http-server globally (one time)
npm install -g http-server

# Run the server
http-server -p 8000
```

Then open: `http://localhost:8000`

### Option 4: PHP Built-in Server
If you have PHP installed:

```bash
php -S localhost:8000
```

Then open: `http://localhost:8000`

### Option 5: VS Code Live Server
If you're using VS Code:
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Features

- **Responsive Design**: Mobile-first approach with breakpoints for tablet and desktop
- **Modern CSS**: Uses CSS variables, Flexbox, and Grid
- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript
- **Accessible**: Semantic HTML and ARIA labels
- **SEO Optimized**: Meta tags and proper heading structure

## Design System

### Colors
- Primary: `#c69c6d` (Golden/Bronze)
- Dark Blue: `#000d44`
- Text Primary: `#54595f`
- Text Secondary: `#7a7a7a`

### Typography
- Font Family: Montserrat (Google Fonts)
- Base Size: 15px
- Headings: 18px - 40px

### Breakpoints
- Mobile: 767px and below
- Tablet: 768px - 1024px
- Desktop: 1025px and above

## Pages

1. **Homepage (index.html)**
   - Hero section with background image
   - About section
   - Features showcase
   - Products preview
   - Call-to-action section

2. **Products (products.html)**
   - Hero section
   - Product grid with cards
   - Features section
   - CTA section

3. **Contact (contact.html)**
   - Hero section
   - Contact information cards
   - Contact form

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Development

### Local Development
Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

### Customization

All design variables are defined in `css/style.css` under `:root` selector. Modify these to change colors, fonts, and spacing.

## Original Source

Converted from WordPress backup located in `backup/` directory. Original site used:
- WordPress with Astra theme
- Elementor page builder
- Various plugins

## License

This is a converted static version of the original WordPress site.
