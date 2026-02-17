# Automatifan.rs - WordPress to HTML/CSS Conversion

## Project Analysis

### Site Overview
- **Domain**: automatifan.rs
- **Language**: Serbian
- **Purpose**: Vending machine business website (coffee machines, office vending machines, self-service machines)
- **Original Platform**: WordPress with Astra theme + Elementor page builder

### Design System

#### Typography
- **Primary Font**: Montserrat (Google Fonts)
- **Font Sizes**:
  - Site Title: 35px (2.333rem)
  - H1/Page Titles: 40px (2.667rem)
  - H2: 30px (2rem)
  - H3: 25px (1.667rem)
  - H4: 20px (1.333rem)
  - H5: 18px (1.2rem)
  - Body: 15px (1rem)
  - Line Height: 1.8em for body text

#### Color Palette
- **Primary Accent**: #c69c6d (Golden/Bronze)
- **Dark Blue**: #000d44
- **Dark Background**: #0c0c0c, #26100b
- **Text Primary**: #54595f
- **Text Secondary**: #7a7a7a
- **Text Light**: #ededed, #ffffff
- **Background**: #ffffff
- **Gradients**: 
  - Dark: linear-gradient(180deg, #000d44 0%, #26100b 100%)
  - Light: linear-gradient(180deg, #ffffff 0%, #dddddd 100%)

#### Layout
- **Container Max Width**: 1140px
- **Responsive Breakpoints**:
  - Desktop: 1025px+
  - Tablet: 768px - 1024px
  - Mobile: 767px and below
- **Spacing**: 100px vertical padding for sections, 50px for smaller sections

### Page Structure

#### 1. Homepage (Page 10)
- Full-height hero section with:
  - Background image: office vending machines
  - Gradient overlay
  - Large heading (3.7vw)
  - Subheading (2.9vw)
  - Description text
  - CTA button (golden #c69c6d)
- Content sections with:
  - Section titles (45px)
  - Divider elements (slashes)
  - Product images (70% width)
  - Description text
  - CTA buttons

#### 2. Products Page (Page 14)
- Full-height hero with self-service machines background
- Grid layout with product cards:
  - Product images (65% width)
  - Product titles (25px)
  - Product descriptions
  - Hover effects with color overlay

#### 3. Contact Page (Page 16)
- Hero section with contact background image
- Contact information cards:
  - Icons (30px)
  - Titles (21px, uppercase, bold)
  - Descriptions
  - Three-column layout

### Components

#### Buttons
- Background: #c69c6d
- Text: #ffffff
- Padding: 15px 45px
- Border radius: 3px
- Box shadow: 6px 8px 10px rgba(122,122,122,0.28)
- Hover: #939393 background
- Font: Montserrat, 15px, 600, uppercase

#### Headings
- Font: Montserrat
- Weight: 700-900
- Color: #ffffff (on dark) or #54595f (on light)

#### Dividers
- Style: Slashes
- Color: rgba(0,0,0,0.34)
- Width: 33% (left-aligned) or centered
- Pattern height: 20px

### Images
- Office vending machines
- Coffee machines
- Self-service machines
- Contact page background

## Conversion Plan

### Phase 1: Project Setup
1. Create project structure
2. Set up HTML5 boilerplate
3. Import Google Fonts (Montserrat)
4. Create base CSS with design system variables
5. Set up responsive breakpoints

### Phase 2: Core Components
1. Header/Navigation
   - Logo area
   - Navigation menu
   - Mobile menu toggle
2. Footer
   - Footer content sections
   - Copyright
3. Button component
4. Typography styles
5. Layout containers

### Phase 3: Page Templates
1. Homepage
   - Hero section
   - Content sections
   - Product showcases
2. Products Page
   - Hero section
   - Product grid
3. Contact Page
   - Hero section
   - Contact cards

### Phase 4: Responsive Design
1. Tablet optimizations
2. Mobile optimizations
3. Image optimization
4. Touch-friendly interactions

### Phase 5: Polish
1. Animations and transitions
2. Hover effects
3. Loading states
4. Accessibility improvements
5. SEO meta tags

### File Structure
```
fan-web/
├── index.html (Homepage)
├── products.html
├── contact.html
├── css/
│   ├── style.css (Main stylesheet)
│   ├── components.css (Reusable components)
│   └── responsive.css (Media queries)
├── js/
│   └── main.js (Navigation, interactions)
├── images/
│   └── [images from backup]
└── README.md
```

## Technical Requirements

### HTML5
- Semantic HTML
- Accessibility attributes
- SEO-friendly structure

### CSS3
- CSS Variables for theming
- Flexbox/Grid for layout
- Modern CSS features
- No external frameworks (vanilla CSS)

### JavaScript
- Vanilla JS only
- Mobile menu toggle
- Smooth scrolling
- No dependencies

### Performance
- Optimized images
- Minimal CSS
- Fast loading
- Mobile-first approach

## Content to Extract

### Images Needed
- Logo (if available)
- Hero background images
- Product images
- Contact page background

### Text Content
- Site title/tagline
- Navigation items
- Page headings
- Product descriptions
- Contact information
- Footer content
