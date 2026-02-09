# Notioneers Brand Guidelines

> **Für KI-Systeme:** Diese Guideline definiert die visuelle Identität von Notioneers. Nutze diese Werte exakt bei der Generierung von Code, Designs und Inhalten.

---

## Brand Essence

**Tagline:** Notion erfolgreich im Unternehmen einführen

**Core Values:**
- Empowering Structure – Systeme die befähigen, nicht einschränken
- Expert Partners – Teil des Teams, nicht externe Berater
- Effortless Efficiency – Klarheit schafft Effizienz

---

## Color System

### Primary Colors (Logo & Text)

| Vorschau | Name | Hex | RGB | Verwendung |
|----------|------|-----|-----|------------|
| ![Depth](https://placehold.co/40x40/063312/063312) | **Depth** | `#063312` | rgb(6, 51, 18) | Primäre Schriftfarbe, Überschriften, Logo auf hellem Hintergrund |
| ![Halo](https://placehold.co/40x40/F2F4F2/F2F4F2) | **Halo** | `#F2F4F2` | rgb(242, 244, 242) | Primärer Hintergrund, Flächen, Sektionen |
| ![Bloom](https://placehold.co/40x40/92EF9A/92EF9A) | **Bloom** | `#92EF9A` | rgb(146, 239, 154) | Logo auf dunklem Hintergrund, Markenakzent |
| ![Shade](https://placehold.co/40x40/0B1E0F/0B1E0F) | **Shade** | `#0B1E0F` | rgb(11, 30, 15) | Dunkler Hintergrund, Dark Mode |

### Logo-Kombinationen (NICHT ÄNDERN)

```
Light Mode:  Depth (#063312) auf Halo (#F2F4F2) oder Transparent
Dark Mode:   Bloom (#92EF9A) auf Shade (#0B1E0F)
```

### Neutral Colors

| Vorschau | Name | Hex | Verwendung |
|----------|------|-----|------------|
| ![Root](https://placehold.co/40x40/454F45/454F45) | **Root** | `#454F45` | Sekundärtext, Icons, dunkle Flächen |
| ![Stone](https://placehold.co/40x40/7B847B/7B847B) | **Stone** | `#7B847B` | Tertiärtext, Linien, subtile UI-Elemente |
| ![Sage](https://placehold.co/40x40/AFCAAF/AFCAAF) | **Sage** | `#AFCAAF` | Borders, Strokes, Trennlinien |
| ![Veil](https://placehold.co/40x40/D1E2D1/D1E2D1) | **Veil** | `#D1E2D1` | Hover-States (Secondary Button), subtile Container |
| ![Mist](https://placehold.co/40x40/DEECDC/DEECDC) | **Mist** | `#DEECDC` | Sekundäre Hintergründe, große Container |
| ![Halo](https://placehold.co/40x40/F2F4F2/F2F4F2) | **Halo** | `#F2F4F2` | Primärer Hintergrund |

### Accent Colors (Interaktiv)

| Vorschau | Name | Hex | Verwendung |
|----------|------|-----|------------|
| ![Pulse](https://placehold.co/40x40/61DB6B/61DB6B) | **Pulse** | `#61DB6B` | Accent-CTAs (sparsam, max. 1x pro Bereich), Success-Borders |
| ![Grove](https://placehold.co/40x40/172D1B/172D1B) | **Grove** | `#172D1B` | Hover-States, Active-States, Dark-Mode-Container |
| ![Ease](https://placehold.co/40x40/B5F5B7/B5F5B7) | **Ease** | `#B5F5B7` | Success-Badges (immer mit Pulse-Border kombinieren) |

### Extended Palette (Nur bei Bedarf)

Nutze diese Farben sparsam für spezifische Use Cases:

| Name | Light | Standard | Bold | Verwendung |
|------|-------|----------|------|------------|
| **Aeris (Blau)** | ![](https://placehold.co/20x20/C1E2F1/C1E2F1) `#C1E2F1` | ![](https://placehold.co/20x20/ACD6EF/ACD6EF) `#ACD6EF` | ![](https://placehold.co/20x20/52B4D9/52B4D9) `#52B4D9` | Links, Informationen |
| **Nimbus (Violett)** | ![](https://placehold.co/20x20/BBB9FF/BBB9FF) `#BBB9FF` | ![](https://placehold.co/20x20/898AE3/898AE3) `#898AE3` | ![](https://placehold.co/20x20/5453CB/5453CB) `#5453CB` | Sekundäre CTAs |
| **Muse (Pink)** | ![](https://placehold.co/20x20/F0D8FF/F0D8FF) `#F0D8FF` | ![](https://placehold.co/20x20/CBA8E8/CBA8E8) `#CBA8E8` | ![](https://placehold.co/20x20/BD73ED/BD73ED) `#BD73ED` | Dekorative Akzente |
| **Coral (Rot)** | ![](https://placehold.co/20x20/FFD2D2/FFD2D2) `#FFD2D2` | ![](https://placehold.co/20x20/DBB0AF/DBB0AF) `#DBB0AF` | ![](https://placehold.co/20x20/ED6767/ED6767) `#ED6767` | Fehler, Warnungen |
| **Solea (Gelb)** | ![](https://placehold.co/20x20/FFF4D0/FFF4D0) `#FFF4D0` | ![](https://placehold.co/20x20/F9E8AF/F9E8AF) `#F9E8AF` | ![](https://placehold.co/20x20/FFDB76/FFDB76) `#FFDB76` | Hinweise, Info-Boxen |
| **Cove (Orange)** | ![](https://placehold.co/20x20/F5DCBC/F5DCBC) `#F5DCBC` | ![](https://placehold.co/20x20/E5C0A8/E5C0A8) `#E5C0A8` | ![](https://placehold.co/20x20/F2AA7F/F2AA7F) `#F2AA7F` | Warme Akzente |

---

## Typography

### Font Family

```css
--font-primary: "TWKLausanne-300", system-ui, sans-serif;
--font-bold: "TWKLausanne-600", system-ui, sans-serif;
```

### Font Weights
- **Regular (300):** Fließtext, UI-Elemente, Überschriften, Buttons
- **Bold (600):** Nur für Emphasis innerhalb von Fließtext (z.B. `<strong>`)

### Verfügbare Schnitte

| Datei | Gewicht | Stil | Pfad |
|-------|---------|------|------|
| TWKLausanne-300 | 300 | Regular | `assets/fonts/web/TWKLausanne-300.woff2` |
| TWKLausanne-300Italic | 300 | Italic | `assets/fonts/web/TWKLausanne-300Italic.woff2` |
| TWKLausanne-400 | 400 | Regular | `assets/fonts/web/TWKLausanne-400.woff2` |
| TWKLausanne-400Italic | 400 | Italic | `assets/fonts/web/TWKLausanne-400Italic.woff2` |
| TWKLausanne-600 | 600 | Bold | `assets/fonts/web/TWKLausanne-600.woff2` |
| TWKLausanne-600Italic | 600 | Bold Italic | `assets/fonts/web/TWKLausanne-600Italic.woff2` |

Desktop-Formate (OTF) liegen in `assets/fonts/desktop/`.

### Empfohlene Größen

| Element | Size | Weight | Line Height |
|---------|------|--------|-------------|
| H1 | 48px / 3rem | 300 | 1.2 |
| H2 | 36px / 2.25rem | 300 | 1.25 |
| H3 | 24px / 1.5rem | 300 | 1.3 |
| H4 | 20px / 1.25rem | 300 | 1.4 |
| Body | 16px / 1rem | 300 | 1.6 |
| Small | 14px / 0.875rem | 300 | 1.5 |
| Caption | 12px / 0.75rem | 300 | 1.4 |

---

## Logo

### Aufbau

Das Notioneers-Logo besteht aus zwei Elementen:
- **Signet (N):** Das stilisierte "N" – kann alleinstehend verwendet werden
- **Wortmarke:** Der ausgeschriebene Schriftzug "notioneers"

Optional kommt eine Illustration mit **Eyes** (Augen-Charakter) hinzu, die der Marke Persönlichkeit verleiht.

### Varianten – Signet (N)

| Datei | Beschreibung | Verwendung |
|-------|--------------|------------|
| `N-Depth-Halo.svg` | Depth-N auf Halo-Hintergrund | Standard, helle Oberflächen |
| `N-Depth-Transparent.svg` | Depth-N auf transparent | Über Fotos, helle Hintergründe |
| `N-Bloom.svg` | Bloom-N auf Depth-Hintergrund | Dark Mode, dunkle Oberflächen |
| `N-Bloom-Eyes.svg` | Bloom-N mit Eyes auf Depth | Dark Mode, persönlich/spielerisch |
| `N-Eyes-Depth-Halo.svg` | Depth-N mit Eyes auf Halo | Light Mode, persönlich/spielerisch |
| `N-Eyes-Depth-Transparent.svg` | Depth-N mit Eyes auf transparent | Über Fotos, persönlich |
| `N-Circle-Depth-Halo.svg` | Depth-N im Kreis auf Halo | Profilbilder, Avatare |
| `N-Circle-Depth-Transparent.svg` | Depth-N im Kreis auf transparent | Profilbilder über Hintergründen |
| `N-Circle-Bloom-Circle.svg` | Bloom-N im Kreis auf Depth | Profilbilder Dark Mode |
| `N-Circle-Bloom-Eyes.svg` | Bloom-N mit Eyes im Kreis | Avatar Dark Mode, spielerisch |
| `N-Circle-Eyes-Depth-Halo.svg` | Depth-N mit Eyes im Kreis auf Halo | Avatar Light Mode, spielerisch |

### Varianten – Wortmarke

| Datei | Beschreibung | Verwendung |
|-------|--------------|------------|
| `Notioneers-Depth-Halo.svg` | Depth-Schrift auf Halo | Standard, Header, Dokumente |
| `Notioneers-Depth-Transparent.svg` | Depth-Schrift auf transparent | Über hellen Hintergründen |
| `Notioneers-Depth-Border.svg` | Depth-Schrift mit Border | Auf unruhigen Hintergründen |
| `Notioneers-Depth-Halo-Border.svg` | Depth-Schrift auf Halo mit Border | Kontrastreiche Platzierung |
| `Notioneers-Bloom-Depth.svg` | Bloom-Schrift auf Depth | Dark Mode |
| `Notioneers-Bloom-Depth-Border.svg` | Bloom-Schrift auf Depth mit Border | Dark Mode, kontraststark |

Alle Logos liegen als SVG und @2x PNG in `assets/logos/`.

### Empfohlene Kombinationen

| Kontext | Signet | Wortmarke |
|---------|--------|-----------|
| **Website Header (hell)** | `N-Depth-Halo` | `Notioneers-Depth-Halo` |
| **Website Header (dunkel)** | `N-Bloom` | `Notioneers-Bloom-Depth` |
| **Favicon / Avatar** | `N-Circle-Depth-Halo` | – |
| **Social Media Profil** | `N-Circle-Depth-Halo` | – |
| **Social Media Dark** | `N-Circle-Bloom-Circle` | – |
| **Persönlich / Social** | `N-Eyes-Depth-Halo` | – |
| **Über Fotos** | `N-Depth-Transparent` | `Notioneers-Depth-Transparent` |
| **Dokumente / Print** | `N-Depth-Halo` | `Notioneers-Depth-Halo` |

### Schutzraum

Mindestabstand um das Logo: Höhe des "N" in Notioneers auf allen Seiten.

### Mindestgröße
- Digital: 100px Breite
- Print: 25mm Breite

### Don'ts
- Farben nicht ändern (außer definierte Varianten)
- Nicht verzerren oder rotieren
- Keine Effekte (Schatten, Glow, etc.)
- Nicht auf unruhigen Hintergründen platzieren
- Eyes-Varianten nicht für formelle/offizielle Dokumente verwenden

---

## Icons

31 illustrative Icons in vier Stilvarianten:

| Variante | Ordner | Beschreibung |
|----------|--------|--------------|
| **Depth** | `assets/icons/depth/` | Depth-Farbe (#063312), für helle Hintergründe |
| **Mist** | `assets/icons/mist/` | Mist-Farbe (#DEECDC), für dunkle Hintergründe |
| **Mist-Round** | `assets/icons/mist-round/` | Mit rundem Hintergrund, für Badges/Buttons |
| **Transparent** | `assets/icons/transparent/` | Ohne Hintergrund, flexibel einsetzbar |

### Verfügbare Icons

Board, Book, Book-Open, Bookmark, Brain, Calc, Calendar-Cycle, Cash-Pie, Checkbox, Checklist, Circles, Clock, Eye, Flight, Folder, Goal, Hands, Heart, Lego, Light, Money, Mood, Network, Paint, Person, Question, Saving, Search, Settings, ThumbsUp, Web

Jedes Icon liegt als SVG und @2x PNG vor.

### Verwendungshinweise
- Verwende **Depth**-Icons auf hellen Flächen (Halo, Mist, Veil)
- Verwende **Mist**-Icons auf dunklen Flächen (Depth, Shade, Grove)
- **Mist-Round** eignet sich für Feature-Listen und Karten
- Icons nicht einfärben – nur die vordefinierten Varianten verwenden

---

## Tone of Voice

### Kernprinzipien

1. **Ehrlich & Transparent** – Keine Übertreibungen, realistische Erwartungen
2. **Klar & Präzise** – Direkte Kommunikation, keine unnötigen Fachbegriffe
3. **Praktisch & Lösungsorientiert** – Bodenständig, konstruktiv
4. **Vertrauenswürdig & Sicher** – Professionell, kompetent
5. **Anpassungsfähig** – Unterstützend bei Wachstum, lösungsorientiert bei Herausforderungen

### Keywords (nach Priorität)

**Primär:** Efficient, Expert, Honest, Empathy, Passionate, Human

**Sekundär:** Enthusiastic, Quality, Understanding, Professional, Reliable, Friendly, Fun

**Tertiär:** Cool, Nerd, Flexible, Loyal, Smart, Creative, Curious

### Sprachbeispiele

**So klingt Notioneers:**
> "Wir bauen Systeme, die mit eurem Unternehmen wachsen."
> "Schluss mit verstreuten Daten – alles an einem Ort."

**So nicht:**
> "Revolutionäre KI-gestützte Synergielösungen für maximale Effizienz!"
> "Wir sind die Besten der Branche."

---

## Quick Reference für KI

```
PRIMÄRFARBEN:
- Text/Logo hell: #063312 (Depth)
- Hintergrund hell: #F2F4F2 (Halo)
- Logo dunkel: #92EF9A (Bloom)
- Hintergrund dunkel: #0B1E0F (Shade)

NEUTRAL (hell → dunkel):
#F2F4F2 → #DEECDC → #D1E2D1 → #AFCAAF → #7B847B → #454F45

FONTS:
- Regular: TWKLausanne-300 (Headings, Buttons, Fliesstext)
- Bold: TWKLausanne-600 (nur Emphasis)

LOGOS (wichtigste):
- Light: assets/logos/N-Depth-Halo.svg
- Dark: assets/logos/N-Bloom.svg
- Wortmarke: assets/logos/Notioneers-Depth-Halo.svg

ICONS:
- 31 Icons in 4 Varianten (depth, mist, mist-round, transparent)
- Pfad: assets/icons/{variante}/{name}.svg

UI-KOMPONENTEN: → siehe ui-guidelines.md
```

---

*Version 2.1 – Notioneers Brand Guidelines*
*UI-Komponenten, Dark Mode, Accessibility: → `ui-guidelines.md`*
