# Portfolio VFX Editor - Landing Page

## Project Overview
- **Type**: Single-page portfolio for a music video VFX editor
- **Core functionality**: Hero video showcase with interactive project grid
- **Target users**: Music artists, directors, producers looking for VFX editing services

## Visual & Rendering Specification

### Layout
- **Hero Section**: Full-viewport video player (100vw x 100vh) with overlay title
- **Projects Grid**: 3-column responsive grid below hero, cards with hover interactions
- **Footer**: Minimal contact/social links

### Typography
- **Font**: "Bebas Neue" (display headings) + "Inter" (body) from Google Fonts
- **Colors**: Dark theme - black background (#0a0a0a), white text (#fafafa), accent gold (#d4af37), VFX tag yellow (#f7d774)

### Visual Style
- Cinematic, dark, minimal
- Subtle grain texture overlay
- Smooth transitions and hover effects

## Header
- **Logo**: "Juan González VFX"
- **Navigation**: REEL, Contacto buttons on left
- **Social Icons**: Instagram, Vimeo, LinkedIn, YouTube (SVG icons)
- **Mobile**: Hamburger menu with full-screen overlay

## Hero Section
- **Title**: "Juan González <span>VFX</span>"
- **Subtitle**: "VFX Artist • Music Videos • Visual Effects • Motion Graphics"
- **Video**: Vimeo embed

## Portfolio Section
- **Projects Grid**: 34 project cards in responsive grid (3→2→1 columns)

### Hero Video
- Vimeo iframe embed
- Full contained within decorative border

### Project Grid
- 34 project cards in responsive grid (3→2→1 columns)
- **Hover effect**: Green overlay (#2a5a3a at 85% opacity) with centered title fade-in animation
- **Grid spacing**: 0.5rem gap for compact, organized layout
- Click: opens YouTube video in new tab

### Animations
- Fade-in on scroll for grid items
- Smooth opacity/transform transitions (300ms ease)
- **Custom cursor**: Green glow (#2a5a3a) with trailing effect on mouse movement

## Footer
- Social icons: Instagram, Vimeo, LinkedIn, YouTube (SVG)

## Acceptance Criteria
1. Hero video fills viewport and loops automatically
2. Grid displays all projects in 3-column layout
3. Clicking a card opens YouTube in new tab
4. Hover effects work on all cards
5. Responsive: 3 columns → 2 columns → 1 column on mobile
6. No console errors
