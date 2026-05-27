# Inspo — Bake & Brew (Branche: Boutique Café + Bakery)

## Übergeordnete Richtung
Editorial Pastel-Café-Look mit großzügigem Weiß-/Cremeraum, kraftvoller Display-Serif Headlines kombiniert mit ruhiger Grotesk-Sans, und einem Farb-Duo aus weichem Türkis + Matcha-Grün als brand-identifiziertes Akzent-System. Hero ist photo-driven (Drink + Pastry), das Layout arbeitet mit Asymmetrie und einer botanischen, ruhigen Bildsprache — keine harte Bakery-Klischees, sondern Specialty-Cafe-Sensibility wie sie auf Dribbble in der Matcha-Brand- und Patisserie-Kategorie dominiert (Limited inspo: 2 Such-Grids ausgewertet, keine Einzelshots im Detail).

## Referenzen (Grid-Synthese)

### 1. Editorial Pastel Café (Mehrere Shots im cafe-bakery Grid)
- URL: dribbble.com/search/cafe-bakery-website
- Stil: warm cream + green accent, big serif, bento layout
- Übernehmen:
  - Big Display-Serif Headline mit feinen Italic-Akzenten
  - Asymmetrischer Hero (große Image rechts, Stack aus Overline / Headline / CTA links)
  - 2x2 oder 2x3 Pastry-Grid mit unterschiedlichen Bild-Heights
- Screenshot: inspo/grid.png

### 2. Matcha-Brand Editorial (matcha-cafe Grid)
- URL: dribbble.com/search/matcha-cafe-website
- Stil: pastel green hero, generous whitespace, photo-heavy
- Übernehmen:
  - Botanischer Schwung (kleine Leaf-Glyphs in Section-Dividern oder als Hintergrund-Watermark)
  - Hero-Image mit weichem Edge-Treatment statt harter Border
  - Drink-Karten als Grid mit großzügiger Padding
- Screenshot: inspo/matcha-search.png

### 3. Cozy-Cafe Photography
- Stil: warm wood, soft daylight, latte-art close-ups
- Übernehmen:
  - Ken-Burns Subtilität auf Hero
  - Maps-Fotos mit Duotone-Filter um Sammelsurium-Charakter zu glätten

### 4. Patisserie Showcase
- Stil: clean grid + serif numerals
- Übernehmen:
  - Specials/Menu mit Roman-Numeral Labels (I · Croissant, II · Matcha-Latte, …) → übersetzt für Café-Kontext zu „Specials 01 / 02 / 03"

### 5. Tea-Brand Botanical
- Stil: green-on-cream, leaf vignette
- Übernehmen:
  - Footer-Marquee mit Tag-Sammlung (Matcha · Coffee · Pastries · Wiesbaden · Open Daily)
  - Section-Background-Watermark mit ovalem Brand-Emblem (Lookback auf das Logo)

## Konkrete Anpassungen für Phase 6
- **Font-Pair**: `Cormorant Garamond` (Serif Display + Headlines) + `Inter` (Sans Body + Overlines) — Cormorant transportiert die boutique-editorial Anmutung, Inter hält den modernen Café-Look ruhig.
- **Hero-Treatment**: split-asymmetrisch — links Overline → große Serif-Headline „Bake. Brew. Be happy." → Tag-Trio → CTA-Paar (Reserve a table / Find us). Rechts großes, gradient-getragenes Hero-Visual mit subtilem Türkis→Matcha-Wash und Pastry/Matcha-Latte als Sujet. Mobile: vollflächig, Headline überlagert das Visual.
- **Section-Flourishes**:
  - „Specials"-Bento-Grid mit zwei Hero-Karten + drei Standard-Karten (asymmetric)
  - „Story"-Block als Image-Text-Split (Atelier-Stil → Bäcker-Hand mit Croissant / Matcha-Whisk)
  - „Reviews"-Block als 3-Spalten Pull-Quote-Karten, Original-Sprachen (EN + DE) sichtbar, Quelle „Google · 4.8 ★"
  - Vollbreiter **Google-Maps-Embed** als eigene Section vor dem Footer — iframe mit echter Maps-URL
- **Mikro-Interaktionen-Highlights**:
  - Magnetic-Button auf CTA „Find us on Maps"
  - Fade-up-on-scroll für alle Section-Headlines (IntersectionObserver, dezent)
  - Hover-Scale + sanftes Hue-Shift in Richtung Türkis auf Specials-Karten
- **Farb-Mood-Hinweis**: Türkis als Hauptakzent (Buttons, Links, Section-Dividers), Matcha als sekundärer botanischer Touch (Hover, Tag-Pills, Leaf-Watermark, Hero-Wash-Tone). Background bleibt warm-cream off-white, Text dunkelnavy/anthrazit für Mobil-Lesbarkeit.

## Hinweise
- Limited inspo (nur 2 Grid-Screenshots, keine einzelnen Shot-Pages durchgeklickt) — Patterns aus dem Such-Grid abgeleitet, nicht 1:1 kopiert.
- Mobile-First-Layout ist Pflicht (User-Vorgabe): Hero wird im Mobile-Breakpoint einspaltig, Specials-Bento kollabiert zu 1-spaltigem Stack mit Carousel-Hint, Maps-Embed bleibt vollbreit.
