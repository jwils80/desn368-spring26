# Cougar Puberty™ — Landing Page

A conversion-focused landing page for Cougar Puberty™, a menopause/perimenopause survival brand built on humor, practical relief, and community solidarity.

## Design System

- **Colors:** Cream (#F8F3EA), Dark (#111), Gold (#D8A73C), Coral (#D96C6C), Slate (#556772), Sage (#8AA17D), Teal (#2F5D62), Plum (#3E2F40)
- **Typography:** Kranky (display), Montserrat (body, weights 300–700), Nothing You Could Do (handwritten accent)

## CSS Transform

`transform: translateY(-4px)` applied to buttons and feature cards on hover — creates a lift effect that signals interactivity.

## CSS Animation

`@keyframes fadeSlideUp` — feature cards fade in and slide up on page load with staggered delays (0.1s, 0.2s, 0.3s).

## Table Content Type

**Product Specifications** — a Symptoms & Survival Guide table with 3 columns (Symptom, What It Feels Like, Survival Tip) and 5 data rows covering common menopause symptoms.

## Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| Translating Figma's scrapbook aesthetic to CSS | Used rotated sticky note cards with distinct colors and box shadows to replicate the handmade feel |
| Missing table/form in the Figma design | Added a Symptoms & Survival Guide table and a contact form that match the brand voice and visual system |
| Responsive table on mobile | Switched to card-style layout using `data-label` attributes so each row becomes a stacked card on small screens |
| Video responsiveness | Used `aspect-ratio: 16/9` wrapper with 100% width for proper scaling |

## Key Learnings

- Translating a scrapbook-style Figma design into semantic CSS requires creative use of transforms, colors, and typography
- Mobile-first table strategies (stacked cards) preserve readability without sacrificing content
- CSS animations with staggered delays create polished, engaging page loads
- Form validation states (default, focus, error, success) improve UX and meet accessibility requirements
