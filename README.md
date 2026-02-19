# MyVivaTour - 10 Days Vietnam Luxury Tour Landing Page

Marketing landing page for MyVivaTour's premium 10-day Vietnam tour package targeting Australian and Southeast Asian travelers.

## Quick Start

1. **Open locally**: Simply open `index.html` in a modern web browser
   ```
   open index.html
   ```

2. **Deploy**: Copy `index.html` to any static hosting (Vercel, Netlify, GitHub Pages, AWS S3, etc.)

## Project Structure

```
.
├── index.html              # Main landing page (262 lines)
├── README.md              # This file
└── docs/                  # Documentation
    ├── project-overview-pdr.md
    ├── codebase-summary.md
    ├── code-standards.md
    ├── system-architecture.md
    ├── design-guidelines.md
    └── project-roadmap.md
```

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **Font Awesome 6.0** - Icons (CDN)
- **Google Fonts** - Playfair Display (headings), Plus Jakarta Sans (body)
- **Vanilla JavaScript** - Mobile menu toggle (~30 lines)

**No build tools, no package manager, no dependencies to install.**

## Key Features

- **Single-page design** with 7 sections (header, hero, destinations, why us, itinerary, testimonials, CTA, footer)
- **Responsive layout** - mobile-first design, optimized for all devices
- **Lead capture form** - "Get a Quote" form in hero section (form processing not yet implemented)
- **Performance optimized** - CDN-hosted assets, minimal JS, fast load times
- **SEO ready** - Open Graph, Twitter Card, canonical URL, meta tags
- **Accessibility** - ARIA labels, semantic HTML, keyboard navigation

## Content Sections

| Section | Purpose |
|---------|---------|
| Header | Navigation with fixed positioning, responsive mobile menu |
| Hero | Full-screen background with lead capture form |
| Destinations | 6 iconic Vietnamese cities in circular grid |
| Why Us | 3 differentiators: Local Experts, Luxury Stays, 24/7 Support |
| Itinerary | Day-by-day 10-day tour overview |
| Testimonials | 3 reviews from Australia, Singapore, Malaysia |
| CTA | Final conversion prompt |
| Footer | Copyright and branding |

## Design System

**Colors:**
- Gold: `#D4AF37` - primary accent
- Dark Green: `#004225` - primary dark
- Slate-50: Light background
- White: Content backgrounds

**Typography:**
- Playfair Display - All headings (serif, elegant)
- Plus Jakarta Sans - Body text (sans-serif, modern)

**Spacing:** Responsive padding/margin using Tailwind scales

## Images

All images from Unsplash (external CDN). No local image files needed.

## Next Steps

See `/docs/project-roadmap.md` for planned features and improvements.

## Documentation

- **[Project Overview & PDR](./docs/project-overview-pdr.md)** - Goals, target audience, success metrics
- **[Codebase Summary](./docs/codebase-summary.md)** - Code structure breakdown
- **[Code Standards](./docs/code-standards.md)** - Naming conventions, patterns
- **[System Architecture](./docs/system-architecture.md)** - Tech stack, dependencies, form processing
- **[Design Guidelines](./docs/design-guidelines.md)** - Colors, typography, component patterns
- **[Project Roadmap](./docs/project-roadmap.md)** - Current state, next phases

---

Last updated: 2026-02-19
