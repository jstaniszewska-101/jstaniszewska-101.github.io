---
tags: [website, brand, design]
created: 2026-07-26
url: https://jstaniszewska-101.github.io/brand.html
---

# Joanna Staniszewska — Brand Guidelines

Live: https://jstaniszewska-101.github.io/brand.html

---

## Logo

Dwie spirale — różana (outer world) i indigo (inner world) — które zbiegają się w jedną linię.  
**Znaczenie:** They do not merge into sameness; they arrive together.

**Warianty:**
- Light background — spirale na kremie
- Dark background — spirale na głębokim indigo

**Clear space:** minimum padding = szerokość jednego koła spirali.

**Zasady:**
- Logo tylko na kremowym lub ciemnym indigo tle
- Nigdy na fotograficznym tle

### SVG (logo mark)

```svg
<svg width="80" height="134" viewBox="0 0 120 200" fill="none" xmlns="http://www.w3.org/2000/svg">
  <!-- Left spiral (rose) -->
  <circle cx="35" cy="20" r="5" stroke="#BE8B85" stroke-width="1.5" fill="none" opacity="0.7"/>
  <circle cx="35" cy="20" r="2" fill="#BE8B85" opacity="0.5"/>
  <!-- Right spiral (indigo) -->
  <circle cx="85" cy="20" r="5" stroke="#7b6fa0" stroke-width="1.5" fill="none" opacity="0.7"/>
  <circle cx="85" cy="20" r="2" fill="#7b6fa0" opacity="0.5"/>
  <!-- Rose path -->
  <path d="M 35 25 C 35 55, 55 80, 60 110" stroke="#BE8B85" stroke-width="1.8" stroke-linecap="round" fill="none"/>
  <!-- Indigo path -->
  <path d="M 85 25 C 85 55, 65 80, 60 110" stroke="#7b6fa0" stroke-width="1.8" stroke-linecap="round" fill="none"/>
  <!-- Merged line -->
  <path d="M 60 110 L 60 168" stroke="url(#mergeGrad)" stroke-width="1.8" stroke-linecap="round"/>
  <circle cx="60" cy="174" r="4.5" stroke="url(#mergeGrad)" stroke-width="1.5" fill="none" opacity="0.8"/>
  <circle cx="60" cy="174" r="1.8" fill="#BE8B85" opacity="0.6"/>
  <defs>
    <linearGradient id="mergeGrad" x1="60" y1="110" x2="60" y2="180" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#BE8B85"/>
      <stop offset="100%" stop-color="#7b6fa0"/>
    </linearGradient>
  </defs>
</svg>
```

---

## Paleta kolorów

### Primary

| Nazwa | HEX |
|-------|-----|
| Dusty Rose | `#BE8B85` |
| Deep Indigo | `#1e1a38` |
| Warm Cream | `#FAF8F6` |

### Accent

| Nazwa | HEX |
|-------|-----|
| Rose Light | `#EDD9D6` |
| Lavender | `#c5b8e8` |
| Gold | `#d4af7a` |
| Indigo Mid | `#7b6fa0` |
| Rose Deep | `#9E6B65` |

**Zasady:**
- Rose + warm cream — tak. Rose + bright white — nie.
- Nie mieszaj day-palette i night-palette w tej samej sekcji.
- Nie stawiaj rose i indigo przy sobie na równym nasyceniu.

---

## Typografia

### Cormorant Garamond — nagłówki i proza

| Użycie | Rozmiar | Styl |
|--------|---------|------|
| Display | 48px | weight 300 |
| H1 | 32px | weight 300 |
| H2 | 24px | weight 300, italic |
| Body | 18px | weight 300, line-height 1.85 |
| Caption | 14px | weight 500 |

### Inter — labels, nawigacja, przyciski

| Użycie | Rozmiar | Styl |
|--------|---------|------|
| Nav | 11px | weight 400, letter-spacing 0.14em, uppercase |
| Label | 10px | weight 500, letter-spacing 0.22em, uppercase |
| Body | 14px | weight 400, line-height 1.72 |
| Button | 11px | weight 400, letter-spacing 0.12em, uppercase |

**Zasady:**
- Italic = ton wewnętrzny / refleksyjny
- Body text bez bold — lekkość jest celowa
- Nagłówki sentence case; ALL CAPS tylko dla micro-labels
- Tylko dwie rodziny czcionek

---

## Zasady użycia

### Do ✓
- Cormorant Garamond dla nagłówków, taglines i prozy
- Inter dla labels, nawigacji, przycisków
- Rose na kremowym tle
- Logo na kremie lub ciemnym indigo
- Generous white space
- Italic dla tonu wewnętrznego
- Sentence case dla nagłówków

### Don't ×
- Logo na fotograficznym tle
- Bold w body text
- Dystorsja lub rotacja logo
- Rose i indigo przy sobie na równym nasyceniu
- Więcej niż dwie rodziny czcionek
- Triady i zaprzeczenia w tekstach
- Mieszanie day i night palette w jednej sekcji

---

## Głos i ton

**Jakości:**
- Warm without being soft
- Contemplative without being abstract
- Confident without claiming
- Inviting, never instructing

**Zasady pisania:**
- One sentence — one idea
- Short. Concrete. No hedging.
- Define by what something *is*, never by what it is not
- Avoid triads of parallel phrases
- End on arrival, never on a door left ajar
