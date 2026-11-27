# 🏛️ Maa Sharda Utsav Lawn — Corporate Profile Website

A luxury single-page corporate profile for **Maa Sharda Utsav Lawn** (माँ शारदा उत्सव लॉन), a premier marriage and event lawn venue in Ambedkar Nagar, Uttar Pradesh.

## ✨ Design

- **Palette:** "Editorial Plaster & Espresso" — Espresso `#2C1810`, Plaster `#E8E0D8`, Cream `#F5F0EB`, Burnished Gold `#B8976A`
- **Typography:** Cormorant Garamond (serif headings) + Inter (body)
- **Aesthetic:** Warm, architectural, timeless — luxury editorial style

## 🎬 Motion, Interaction & Performance

- **Native smooth anchor scrolling** — smooth section navigation without scroll hijacking or an extra scroll library.
- **Scroll reveals** — lightweight `IntersectionObserver` reveals, staggered subtly as sections enter view.
- **Counters and interactions** — requestAnimationFrame-based counters, low-cost card hover/tilt effects, and a frame-coalesced sticky-header update.
- **Reduced motion** — animation and smooth-scroll behavior respects the visitor's system preference.
- **Invitation film** — poster loads first; the large video file downloads only when the visitor presses Play.
- **Ambient clips** — clips are loaded near the viewport and paused when they leave it.
- **Gallery films** — long videos use `preload="none"` so they do not compete with the page's initial load.
- **3D tour** — Three.js scripts load after the tour interface markup; render resolution is capped for high-DPI devices without changing the tour's original visual styling.

## 📄 Sections

1. Invitation-led opening section with the wedding film and 3D Banquet link
2. Sticky header with mobile navigation
3. Venue hero with arch-frame photography and key details
4. Cinematic cover photo banner
5. Credibility bar (guest capacity, events and venue details)
6. Scrolling marquee
7. Services grid
8. "Why Choose Us" interactive steps
9. Venue photo gallery and cinema section
10. Testimonials
11. Location and directions
12. Contact section and WhatsApp button

## 📍 Verified Venue Details (Justdial)

- **Official Name:** Maa Sharda Utsav Lawn (माँ शारदा उत्सव लॉन / Ma Sarda Utsav Lawn)
- **Address:** Masdha Bazar Barahi, Akbarpur Road, Bela Parsa, Ambedkar Nagar - 224129, Uttar Pradesh
- **Phone:** `07947134176`
- **Hours:** Monday – Sunday, 07:00 AM – 11:00 PM (Daily)
- **Founded:** January 2023
- **Capacity:** 500 to 2,000+ guests
- **Rating:** 5.0 / 5.0 ★ (Justdial Verified)
- **Google Maps Directions:** [Click here for turn-by-turn navigation](https://www.google.com/maps/dir/?api=1&destination=26.452228527778,82.726181027778)
- **Official Justdial Profile:** [Justdial Listing](https://www.justdial.com/Ambedkar-Nagar/Ma-Sarda-Utsav-Lawn-Masdha-Bazar-Barahi-Bela-Parsa/9999P5271-5271-250609152009-K2M9_BZDET)

## 🚀 Usage

Just open `index.html` in a browser — no build step required. All dependencies load from CDN.

```bash
# Or serve locally
python -m http.server 8787
# Open http://localhost:8787
```

## 📸 Photos

All venue photos in `images/venue/` are sourced from the venue's JustDial listing.

---

*Built with ❤️ — Editorial Plaster & Espresso design system*
