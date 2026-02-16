# Design Rationale – Autumn Salon

## 1. Target Users & Context

- **Primary users:** Working professionals (25–45), students and young adults in Hyderabad.
- **Goals:** 
  - Discover services and pricing quickly
  - Check credibility (photos, reviews, branches)
  - Book an appointment without calling, if possible
- **Devices:** Mostly mobile, with desktop used for deeper browsing or planning.

These insights informed a **mobile‑first layout** and strong emphasis on clear CTAs.

## 2. Information Architecture & Layout

### Homepage

- **Hero section:** 
  - Headline: emotional benefit (“Unleash The Gorgeous You”)
  - Subtext: clarifies offering and value
  - Primary CTA: “Book Now”
- **Services strip:** Key categories (Hair, Face, Men’s Grooming, Bridal, Massages, Mani & Pedi) for quick scanning.
- **Testimonials:** Real‑style quotes and star ratings to build trust.
- **Footer:** Branch details, contact, social links and download badges.

This structure supports a quick path: **Land → Understand → Trust → Book**.

### Services Page

- Grid of service cards with:
  - Image → visual cue
  - Title → clear what it is
  - Short description → what’s included & who it’s for
- Designed to help users compare services and feel confident before booking.

### Booking Page

- Focused 4‑field form:
  - Name
  - Service
  - Date
  - Contact number
- Primary CTA: “Book Now”
- Secondary CTAs: “Call Us Now” and “Text Us” (WhatsApp) for users who prefer direct contact.

### Contact Page

- Clear title: “Reach Out To Us”
- Sections:
  - Social media handles
  - Single email contact
  - Click‑to‑call phone numbers for each branch

## 3. Visual Design Decisions

### Colour

- Primary brand colour: rich maroon for a **premium salon** feel.
- Accent colour: warm yellow for **high‑attention CTAs**.
- Background: soft cream to reduce glare and keep focus on imagery.

### Typography

- Serif for headings (brand personality, elegance).
- Sans‑serif for body text for legibility.
- Type scale:
  - Desktop: H1 48, H2 36, H3 24, Body 18
  - Mobile: H1 32, H2 24, H3 20, Body 16

### Imagery

- Realistic service images: hair care, facials, nails, bridal, men’s grooming.
- Client photos in testimonials to enhance authenticity.

## 4. UX & Conversion Decisions

- **Consistent “Book Now” button** at key points (hero, after services, end of pages).
- **Alternative actions** (call / WhatsApp) to match different user preferences.
- **Service descriptions** written in the pattern: what it is → what’s included → who it’s for.
- **Testimonials** placed after services to support decision making before booking.

## 5. Accessibility & WCAG Considerations

- Minimum **16 px body text** for readability on mobile.
- Form fields sized to at least **48 px height** for comfortable touch targets.
- Clear labels for each input.
- High‑contrast CTAs against the background.
- Planned improvements (not yet coded):
  - Stronger colour contrast for text on maroon backgrounds
  - Visible keyboard focus styles
  - ARIA labels for hamburger menu
  - Error and success states for the booking form

## 6. Learnings

- Designing for **conversion** changes layout decisions (shorter forms, repeated CTAs).
- Accessibility and WCAG guidelines improve both usability and trust.
- Having a consistent design system (type, colour, components) made scaling across pages easier.
