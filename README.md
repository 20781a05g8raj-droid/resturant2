# 👑 Royal Spice - Fine Indian Dining

A luxury, professional single-page restaurant website for an Indian fine dining establishment, featuring parallax effects, full animations, and responsive design.

---

## ✅ Completed Features

### Design & Theme
- **Luxury dark theme** with Gold (#d4af37), Deep Red (#8b0000), and Cream (#f5f0e8) color palette
- **Premium typography**: Playfair Display (headings), Cormorant Garamond (subheadings), Poppins (body)
- CSS variables for easy theme customization
- Gold shimmer / glow effects on important elements
- Subtle decorative patterns and textures throughout

### Parallax Effects
- Full-screen JS-powered parallax hero section
- CSS `background-attachment: fixed` parallax on stats section, reservations section, and divider sections
- Two mid-page parallax divider sections with compelling CTAs

### Animations
- **AOS (Animate On Scroll)** library for scroll-triggered animations (fade-up, fade-left, fade-right, zoom-in)
- Preloader animation with logo pulse, spinner, and bouncing dots
- Navbar: transparent → solid glass effect on scroll
- Floating decorative circle elements on hero
- Hero badge, title, subtitle, and buttons — staggered fade-in animations
- Hover effects on all cards, buttons, and icons
- Counter animations (animated counting numbers for stats)
- Gold shimmer text animation
- Awards marquee scrolling banner
- Smooth hover zoom on gallery images
- Scroll-down indicator animation

### Navigation
- Sticky navbar with smooth scroll to all sections
- Active link highlighting as sections scroll into view
- Hamburger menu for mobile with full-screen overlay
- All 6 nav links + "Book a Table" CTA — all fully functional

### Sections
1. **Home/Hero** — Full-screen parallax, animated headline, dual CTAs, scroll indicator
2. **About** — Restaurant story, floating image with border frame, features grid
3. **Stats** — Parallax background, animated counters (15+ Years, 500+ Dishes, 50000+ Guests, 25 Awards)
4. **Chef** — Executive Chef profile with quote, image, name plate
5. **Menu** — 35+ Indian dishes with category filter (All/Starters/Main/Biryani/Tandoor/Desserts/Beverages), Indian prices (₹), veg/non-veg indicators
6. **Gallery** — 9-item masonry grid with filter by category (Food/Interior/Events), hover overlays, lightbox
7. **Reservations** — Full booking form with date/time/guests/occasion picker, success state
8. **Contact** — Contact info, social links, contact form with feedback, Google Maps embed
9. **Footer** — Logo, quick links, opening hours, newsletter signup, copyright

### Interactivity
- Menu category filter with smooth show/hide animation
- Gallery category filter
- Lightbox image viewer (click to expand, Esc/click-outside to close)
- Reservation form with loading state and success confirmation
- Contact form with sending state and success state
- Newsletter subscription with validation
- Back-to-top button (appears on scroll)
- Toast notification system for user feedback

### Responsiveness
- Mobile-first responsive design
- Hamburger menu for all mobile devices
- Responsive grid layouts (2-col → 1-col on mobile)
- Proper font scaling using `clamp()`
- Touch-friendly targets

---

## 📁 File Structure

```
index.html      ← Complete single-file website (HTML + CSS + JS)
README.md       ← This documentation file
```

---

## 🔗 Entry Points / Navigation

| Section | Anchor |
|---|---|
| Home/Hero | `#home` |
| About Us | `#about` |
| Menu | `#menu` |
| Gallery | `#gallery` |
| Reservations | `#reservations` |
| Contact | `#contact` |

---

## 🍽️ Menu Categories & Price Range

| Category | Items | Price Range |
|---|---|---|
| Starters | 8 items | ₹149 – ₹549 |
| Main Course | 9 items | ₹299 – ₹649 |
| Biryani & Rice | 5 items | ₹149 – ₹599 |
| Tandoor & Breads | 4 items | ₹49 – ₹119 |
| Desserts | 5 items | ₹199 – ₹279 |
| Beverages | 4 items | ₹99 – ₹199 |

---

## 🛠️ Tech Stack & Libraries

- **HTML5** + **CSS3** + **Vanilla JavaScript**
- **Google Fonts**: Playfair Display, Cormorant Garamond, Poppins
- **Font Awesome 6.4**: Icons throughout
- **AOS 2.3.4**: Scroll-triggered animations
- **Unsplash**: High-quality food and restaurant imagery

---

## 📌 Restaurant Details

- **Name**: Royal Spice - Fine Indian Dining
- **Address**: 42, Maharaja Road, Connaught Place, New Delhi – 110001
- **Phone**: +91 98765 43210 | +91 11 4000 1234
- **Email**: reservations@royalspice.in
- **Hours**: Mon–Sun 12:00 PM – 11:00 PM (Sunday Brunch from 11:00 AM)

---

## 🚀 Recommended Next Steps

1. **Backend integration** — Connect reservation and contact forms to a real backend/email service
2. **Database** — Use the Table API to store reservations and contact form submissions
3. **Online ordering** — Add a cart and ordering system for takeout
4. **CMS** — Allow menu updates without code changes
5. **Animations** — Add GSAP for more advanced scroll-triggered animations
6. **SEO** — Add meta tags, Open Graph, structured data for restaurant
7. **PWA** — Make it installable as a Progressive Web App
8. **Reviews Section** — Add customer testimonials/reviews carousel

---

## 🚀 Deployment

To make this website live, go to the **Publish tab** and click Publish. The platform will handle all deployment automatically.

---

*© 2024 Royal Spice. All Rights Reserved.*
