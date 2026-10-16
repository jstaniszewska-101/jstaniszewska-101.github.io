---
date: 2026-06-24
tags: [website, github-pages, guidetoorganizations]
status: in-progress
---

# Website Session — GitHub Pages Redesign
*2026-06-24*

## Co zrobiliśmy

### Strona główna — jstaniszewska-101.github.io
Repo: `jstaniszewska-101/jstaniszewska-101.github.io`

**Zmiany wprowadzone:**
- Paleta kolorów → kolory z okładki książki (lniany / łososiowy / stalowy błękit / granat)
- Usunięto "Being in Systems" i "Systems Thinking" z hero i footera
- Usunięto "Facilitation" z sekcji Work (zostały: Consulting · Writing · Education)
- Tytuł książki: "A Philosophical Guide to Organizations" → **"Guide to Organizations"**
- Spójne `border-radius: 4px` wszędzie (bez mieszania stylów)
- Favicon dodany (maska z okładki)
- Footer: "© 2026" (bez Being in Systems)

**Paleta:**
| Nazwa | Hex | Użycie |
|---|---|---|
| Lniany | `#F4EFE8` | tło |
| Łososiowy | `#D4896A` | akcenty, przyciski |
| Stalowy błękit | `#5A8FA3` | linki, credentials |
| Granat | `#1C3A4A` | tekst główny |

---

## Odpowiedzi na pytania

### Czy GitHub pozwala na więcej niż 3 strony?
**Tak — nieograniczona liczba.** Każde repo może mieć GitHub Pages. Planowane strony:
- `jstaniszewska-101.github.io` → przekieruje na `guidetoorganizations.com`
- `guidetoorganizations.com` → strona główna (o Joannie + o książce)
- `guidetoorganizations.pub` → strona książki *(do zrobienia później)*

### Privacy Policy — czy potrzebna?
**Nie na razie.** Strona jest statycznym HTML bez:
- formularzy zbierających dane
- cookies / analytics
- osadzonego newslettera

Będzie potrzebna gdy: dodasz Google Analytics, formularz Substack/Mailchimp, pixel Meta/LinkedIn.

---

## Domeny

### guidetoorganizations.com (lh.pl)
**Status:** Kupiona, DNS jeszcze nie skonfigurowany.

Gdy gotowa — ustaw w lh.pl rekordy A:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
Potem: GitHub repo → Settings → Pages → Custom domain → `guidetoorganizations.com`

CNAME zostanie dodany do repo dopiero po ustawieniu DNS (żeby uniknąć przekierowania bez działającej domeny).

### guidetoorganizations.pub
**Status:** Do zrobienia później.
Czekamy na: grafiki gotowe + atrybucje Midjourney i Victorii Graci (za jej agenta).

---

## Treść z Canva (strona książki)
Pełny tekst do wykorzystania na guidetoorganizations.pub:
- Hero: *"Stop for a book"* + tagline
- 3 części: The Visible World of Work / The Inner Architecture / The Living Edge
- About the Book (35 esejów)
- For You If (4 punkty)
- Spis rozdziałów Part I / II / III
- Cytaty: Belonging (Ch. 21), Flow
- Bio autorki
- How to get: Amazon + guidetoorganizations.pub

---

## Grafiki książki
Lokalizacja w vaulcie: `Guide to Organizations Book/AKTUALNE/graphics/`
- Favicon / okładka: `Guide to Organization favicon.png`
- Okładka EN: `Cover_EN.png`
- 47 ilustracji rozdziałów (styl akwarelowo-tuszowy)

---

## Do zrobienia

- [ ] Ustawić DNS w lh.pl (4 rekordy A)
- [ ] Dodać CNAME do repo po ustawieniu DNS
- [ ] Aktualne zdjęcie profilowe Joanny (zastąpić obecne)
- [ ] Strona guidetoorganizations.pub — gdy będą grafiki + atrybucje
