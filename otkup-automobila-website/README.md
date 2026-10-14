# Structure of otkup__automobila_ full website package

## Overview
Generated website for otkup__automobila_ business based on Syntax Digital's standard pipeline. This package follows our established design system and development patterns.

## Pages

### 1. `index.html`
**Home page** with hero section and service grid
- Responsive design with gradient navigation
- 4 service cards (Brzi Otop Automobila, Izborna Ponuda, Gotovina odmah, Besplatna Procjena)
- IntersectionObserver reveal animations
- Mobile-first layout with breakpoint at 900px

### 2. `o-nama.html`
**About page** presenting the business
- Team section with placeholder images
- Three value cards (Transparentnost, Brzina, Poštena Vrijednost)
- Responsive grid layout
- Smooth scroll reveal effects

### 3. `usluge.html`
**Services page** with detailed offerings
- Six service cards with descriptions
- Two pricing tiers (Osnovni Paket, Premium Paket)
- Feature lists with checkmarks
- Gradient styling with accent colors

### 4. `kontakt.html`
**Contact page** with form and info
- Contact information with icons
- Formspree integration (https://formspree.io/f/xldjylpy)
- Map placeholder
- Mobile-optimized form layout

### 5. `style.css`
**Shared styles**
- CSS variables for color system
- Glass-morphism navigation with backdrop-filter
- Responsive design with mobile breakpoint
- Smooth transitions and hover effects

## Supporting Files

### 6. `README.md`
**Package documentation** (this file)

### 7. `ponuda.html`
**Formalna ponuda** for sastanak-prodaja

### 8. `dopis`
**Dopis** template for client meeting

### 9. `upute-odrzavanje.txt`
**Maintenance instructions** for website

### 10. `cold-call-skripta.md`
**Cold call script** for lead outreach

### 11. `email-draft.txt`
**Email draft** for client communication

### 12. `sastanak-vodic.md`
**Meeting guide** for client presentation

## Design System

### Colors
- `--primary: #2563eb` (Professional blue)
- `--accent: #10b981` (Success green)
- `--bg: #ffffff` (White background)
- `--text: #111827` (Dark text)

### Typography
- **Headings**: Inter, sans-serif (weights 600-900)
- **Body**: Inter, sans-serif (weights 300-500)

### Layout
- Container: 1200px max-width
- Grid: Auto-fit columns (min 280px)
- Breakpoint: 900px for mobile optimization

## Technical Details

### Files Structure
```
otkup-automobila-website/
├── website/
│   ├── index.html
│   ├── o-nama.html
│   ├── usluge.html
│   ├── kontakt.html
│   └── style.css
├── ponuda.html
├── dopis
├── upute-odrzavanje.txt
├── cold-call-skripta.md
├── email-draft.txt
└── sastanak-vodic.md
```

### Animations
- IntersectionObserver for scroll reveal
- Smooth transitions on all interactive elements
- Hover effects on cards and buttons

### Accessibility
- Semantic HTML5 structure
- ARIA labels and roles
- Keyboard navigation support
- Contrast ratios meet WCAG AA standards

## Deployment

Ready for deployment to GitHub Pages or Vercel. All assets are self-contained with no external dependencies.

## Notes

- Generated using Syntax Digital's established patterns
- Follows existing quality and design standards
- Mobile-first responsive design
- Accessible and performant
