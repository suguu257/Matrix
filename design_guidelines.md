# Matrix Multimedia Club Website Design Guidelines

## Design Approach
**Reference-Based Approach**: Drawing inspiration from Apple's iPad site for fluid transitions combined with cyberpunk aesthetics for futuristic appeal. This hybrid approach balances corporate sophistication with creative boldness.

## Core Design Elements

### Color Palette
**Dark Mode Primary** (matching cyberpunk theme):
- Background: 210 25% 8% (deep midnight blue)
- Surface: 210 20% 12% (elevated dark surfaces)
- Primary: 180 100% 70% (electric cyan)
- Secondary: 280 60% 65% (electric purple)
- Accent: 160 80% 60% (matrix green - use sparingly)
- Text: 210 10% 95% (near white)

**Light Mode** (corporate elegance):
- Background: 210 20% 98% (soft white)
- Surface: 210 15% 95% (glass surfaces)
- Primary: 210 85% 45% (professional blue)
- Secondary: 280 40% 50% (muted purple)

### Typography
- **Primary**: Orbitron (futuristic headings, club name)
- **Secondary**: Inter (body text, UI elements)
- **Hierarchy**: H1: 64px→36px→28px, H2: 48px→28px→24px, Body: 16px→14px

### Layout System
**Tailwind Spacing**: Consistent use of 2, 4, 6, 8, 12, 16 units
- Cards and sections: p-8, gap-6
- Component spacing: m-4, p-2
- Large containers: py-16, px-8

### Component Library
**Navigation**: Glass-morphism header with smooth hamburger on mobile
**Cards**: Frosted glass effect with subtle borders and hover elevations
**Buttons**: Primary (filled), Secondary (outline with blur on images), Ghost variants
**Hero Section**: Full viewport with particle background and holographic text effects
**Gallery**: Masonry grid with smooth modal overlays
**Forms**: Minimal floating labels with cyberpunk accent colors

### Visual Effects
**Glass Morphism**: Semi-transparent surfaces with backdrop-blur
**Particle Systems**: Subtle Matrix-style falling code in background
**Smooth Transitions**: 300ms cubic-bezier easing for all interactions
**Hover States**: Gentle scale transforms and glow effects
**Scroll Animations**: Fade-in and slide-up reveals with intersection observer

### Images
**Hero Image**: Large full-viewport background featuring abstract digital/matrix patterns or club activities with holographic overlay effects
**Team Photos**: Professional headshots with consistent lighting and backgrounds
**Project Gallery**: High-quality screenshots and videos of multimedia work
**Event Images**: Dynamic photos from club activities and competitions
**Background Elements**: Subtle geometric patterns and particle effects

### Performance & Accessibility
- Mobile-first responsive design
- Touch-friendly 44px minimum tap targets  
- Reduced motion support for accessibility
- High contrast ratios (4.5:1 minimum)
- Keyboard navigation support
- Alt text for all visual elements
- Vercel-optimized static generation for fast loading

### Key Pages Structure
1. **Hero Landing**: Matrix-themed with club introduction
2. **About**: Mission, vision, and club philosophy  
3. **Projects**: Interactive showcase gallery
4. **Events**: Futuristic calendar and upcoming activities
5. **Team**: Member profiles with elegant reveals
6. **Contact**: Clean form with glass morphism styling