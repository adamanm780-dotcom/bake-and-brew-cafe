# Bake & Brew

**Slug:** bake-and-brew-v2
**Branche:** Boutique Café & Bakery (Specialty Coffee + Matcha + Patisserie)
**Build-Datum:** 2026-05-27
**Live-URL:** https://adamanm780-dotcom.github.io/bake-and-brew-cafe/
**Repo:** https://github.com/adamanm780-dotcom/bake-and-brew-cafe
**Lokal:** C:/Users/Adria/claude-discord-projects/allgemein/bake-and-brew-v2

## Kontakt
- Adresse: Stettiner Str. 10, 65203 Wiesbaden Biebrich
- Telefon: n/a (nicht öffentlich auf Maps gelistet)
- E-Mail: n/a
- Öffnungszeiten: Mo–Fr 08–18 Uhr, Sa 09–17 Uhr, So geschlossen (Annahme, Maps: „Closes 6 pm")
- Website (Original): n/a (Café hatte vorher keine eigene)
- Instagram: @bakeandbrew.bakery
- Plus Code: 26QQ+7V Wiesbaden

## Design
- Palette: #f7f2e8 (cream bg) · #4cb5b0 (Türkis accent) · #94b87a (Matcha) · #2a3530 (deep ink text) · #c89366 (gold/croissant warm touch) · #fbf8ef (ivory raised)
- Fonts: Cormorant Garamond (Serif Display) + Italiana (Brand-Logo) + Inter (Sans Body)
- Style-Richtung: Editorial Pastel Café · Türkis als Brand-Akzent · Matcha-Grün als botanische Sekundärfarbe · warm-cream Body · mobile-first responsive

## Assets
- Hero: assets/hero.webp (Nano Banana 21:9 → Real-ESRGAN 4K → 368KB WebP) — Matcha-Latte mit Latte-Art + Croissant + Whisk auf Cream-Linen
- Maps-Fotos: n/a (Google Maps Embed direkt eingebunden, keine separaten Fotos)
- Insta-Posts: n/a (kein Direct-Crop, Insta-Handle verlinkt)
- Zusatz-Assets (alle Nano Banana, brand-konsistent):
  - assets/matcha.webp — ceremonial Matcha-Latte close-up
  - assets/croissant.webp — Almond Butter Croissant
  - assets/pour.webp — Hand pouring milk in matcha
  - assets/cake.webp — Raspberry Chocolate Cake slice
  - assets/spread.webp — Pastry-Spread (Croissant, Cookie, Cake, Cinnamon Bun, Espresso, Matcha)
  - assets/about.webp — Café-Interior mit Pflanzen + Marmor-Theke
  - assets/texture.webp — Linen-Texture mit Türkis-Pattern (Background-Reserve)

## Features
- Echte Google-Reviews (3× originalgetreu eingebunden: Nashi Verma, Svetlana Galka, Kyra)
- Google Maps Embed Section (iframe no-API, on Stettiner Str. 10)
- 4,8★ Rating-Pill mehrfach im Layout (Topbar, Hero-Badge, Reviews-Section, Contact-Card)
- Mobile-First Responsive (Breakpoints 540 / 680 / 860 / 1100)
- Hamburger-Mobile-Nav mit fullscreen overlay
- Ken-Burns Hero-Animation
- Reveal-on-Scroll IntersectionObserver
- Marquee mit Brand-Tags (Matcha · Specialty Coffee · Pastry Love · Bake. Brew. Be happy. · Wiesbaden · Biebrich)
- Bento Specials Grid (4-col × 3-row mit Matcha als Hero-Karte)
- Asymmetric Detail-Gallery (4-col × 2-row mit tall/wide-Mods)
- prefers-reduced-motion-Support

## Build-Stats
- Build-Zeit: ~30 min
- Sections im HTML: 11 (Topbar, Header, Hero, Marquee, Intro/Story, Specials, Story-Atelier, Gallery, Reviews, Maps, Contact, Footer)
- Assets-Größe gesamt: ~1.2 MB (8× WebP optimiert)
- Pflicht-Features umgesetzt: Mobile-Responsive ✓, Scroll-Animation (pending !buildscroll) ✓, Türkis+Matcha ✓, echte Reviews ✓, Maps-Integration ✓

## Updates
- 2026-05-27: Initial Build mit Mobile-First Design, Türkis+Matcha-Palette, 3 echten Google-Reviews, Google-Maps-Embed
- 2026-05-27: Scroll-Frame-Animation eingebaut — 50 Frames Matcha-Whisking (Seedance 2.0 → 121 frames extrahiert auf 50, magenta chromakey #ff00ff entfernt via ffmpeg), neue Section „Whisked, not stirred" zwischen Marquee und Story. Sticky-Container fix: overflow:hidden auf .scroll-anim entfernt damit position:sticky funktioniert.
