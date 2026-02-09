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

| Name | Hex | RGB | Verwendung |
|------|-----|-----|------------|
| **Depth** | `#063312` | rgb(6, 51, 18) | Primäre Schriftfarbe, Überschriften, Logo auf hellem Hintergrund |
| **Halo** | `#F2F4F2` | rgb(242, 244, 242) | Primärer Hintergrund, Flächen, Sektionen |
| **Bloom** | `#92EF9A` | rgb(146, 239, 154) | Logo auf dunklem Hintergrund, Markenakzent |
| **Shade** | `#0B1E0F` | rgb(11, 30, 15) | Dunkler Hintergrund, Dark Mode |

### Logo-Kombinationen (NICHT ÄNDERN)

```
Light Mode:  Depth (#063312) auf Halo (#F2F4F2) oder Transparent
Dark Mode:   Bloom (#92EF9A) auf Shade (#0B1E0F)
```

### Neutral Colors

| Name | Hex | Verwendung |
|------|-----|------------|
| **Root** | `#454F45` | Sekundärtext, Icons, dunkle Flächen |
| **Stone** | `#7B847B` | Tertiärtext, Linien, subtile UI-Elemente |
| **Sage** | `#AFCAAF` | Borders, Strokes, Trennlinien |
| **Veil** | `#D1E2D1` | Hover-States (Secondary Button), subtile Container |
| **Mist** | `#DEECDC` | Sekundäre Hintergründe, große Container |
| **Halo** | `#F2F4F2` | Primärer Hintergrund |

### Accent Colors (Interaktiv)

| Name | Hex | Verwendung |
|------|-----|------------|
| **Pulse** | `#61DB6B` | Accent-CTAs (sparsam, max. 1x pro Bereich), Success-Borders |
| **Grove** | `#172D1B` | Hover-States, Active-States, Dark-Mode-Container |
| **Ease** | `#B5F5B7` | Success-Badges (immer mit Pulse-Border kombinieren) |

### Extended Palette (Nur bei Bedarf)

Nutze diese Farben sparsam für spezifische Use Cases:

**Aeris (Blau)** – Informationen, Links
- Light: `#C1E2F1` | Standard: `#ACD6EF` | Bold: `#52B4D9`

**Nimbus (Violett)** – Sekundäre CTAs
- Light: `#BBB9FF` | Standard: `#898AE3` | Bold: `#5453CB`

**Muse (Pink)** – Dekorative Akzente
- Light: `#F0D8FF` | Standard: `#CBA8E8` | Bold: `#BD73ED`

**Coral (Rot)** – Fehler, Warnungen
- Light: `#FFD2D2` | Standard: `#DBB0AF` | Bold: `#ED6767`

**Solea (Gelb)** – Hinweise, Info-Boxen
- Light: `#FFF4D0` | Standard: `#F9E8AF` | Bold: `#FFDB76`

**Cove (Orange)** – Warme Akzente
- Light: `#F5DCBC` | Standard: `#E5C0A8` | Bold: `#F2AA7F`

---

## Typography

### Font Family

```css
--font-primary: "TWKLausanne-300", system-ui, sans-serif;
--font-bold: "TWKLausanne-600", system-ui, sans-serif;
```

### Font Weights
- **Regular (300):** Fließtext, UI-Elemente
- **Bold (600):** Überschriften, Buttons, Emphasis

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
| H1 | 48px / 3rem | 600 | 1.2 |
| H2 | 36px / 2.25rem | 600 | 1.25 |
| H3 | 24px / 1.5rem | 600 | 1.3 |
| H4 | 20px / 1.25rem | 600 | 1.4 |
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

## UI Components

### Designprinzip

Die UI ist minimalistisch und professionell. Neutrale Farben (Depth, Halo, Stone, Sage) dominieren. Pulse und andere Akzentfarben werden sparsam und gezielt eingesetzt – nur dort, wo eine Aktion Aufmerksamkeit erfordert. Die meiste Fläche bleibt ruhig.

### Buttons

**Primary Button (Standard – der häufigste Button)**
```css
background: #063312; /* Depth */
color: #F2F4F2; /* Halo */
border: 1px solid #063312; /* Depth */
border-radius: 8px;
padding: 12px 24px;
font-weight: 600;
```

**Primary Button (Hover)**
```css
background: #172D1B; /* Grove */
border-color: #172D1B; /* Grove */
```

**Accent Button (sparsam – nur für eine zentrale CTA pro Seite)**
```css
background: #61DB6B; /* Pulse */
color: #063312; /* Depth */
border: 1px solid #063312; /* Depth */
border-radius: 8px;
padding: 12px 24px;
font-weight: 600;
```

**Accent Button (Hover)**
```css
background: #063312; /* Depth */
color: #F2F4F2; /* Halo */
border-color: #063312; /* Depth */
```

**Secondary Button**
```css
background: transparent;
color: #063312; /* Depth */
border: 1px solid #AFCAAF; /* Sage */
border-radius: 8px;
padding: 12px 24px;
font-weight: 600;
```

**Secondary Button (Hover)**
```css
background: #D1E2D1; /* Veil */
color: #063312; /* Depth */
border-color: #7B847B; /* Stone */
```

**Ghost Button (minimalistisch, für tertiäre Aktionen)**
```css
background: transparent;
color: #454F45; /* Root */
border: none;
padding: 12px 24px;
font-weight: 600;
```

**Ghost Button (Hover)**
```css
color: #063312; /* Depth */
background: #DEECDC; /* Mist */
```

**Danger Button**
```css
background: #ED6767; /* Coral Bold */
color: #F2F4F2; /* Halo */
border: 1px solid #ED6767; /* Coral Bold */
border-radius: 8px;
padding: 12px 24px;
font-weight: 600;
```

**Danger Button (Hover)**
```css
background: #063312; /* Depth */
color: #ED6767; /* Coral Bold */
border-color: #ED6767; /* Coral Bold */
```

### Button-Hierarchie

```
Seite mit einer klaren Hauptaktion:
  [Accent Button]  [Secondary Button]  [Ghost Button]

Seite ohne klare Hauptaktion (z.B. Dashboard, Formulare):
  [Primary Button]  [Secondary Button]  [Ghost Button]

Regel: Maximal EIN Accent Button pro sichtbarem Bereich.
       Primary (Depth) ist der Standard-Button.
       Pulse nur verwenden, wenn eine Aktion herausstechen muss.
```

### Links

```css
color: #52B4D9; /* Aeris Bold */
text-decoration: underline;
```

**Link (Hover)**
```css
color: #063312; /* Depth */
```

**Link auf dunklem Hintergrund**
```css
color: #ACD6EF; /* Aeris Standard */
```

### Cards

```css
background: #F2F4F2; /* Halo */
border: 1px solid #AFCAAF; /* Sage */
border-radius: 12px;
padding: 24px;
```

### Input Fields

```css
background: #F2F4F2; /* Halo */
border: 1px solid #7B847B; /* Stone – klar sichtbare Feldgrenze */
border-radius: 8px;
color: #063312; /* Depth */
```

**Input (Focus)**
```css
border-color: #063312; /* Depth – dezent, kein Pulse */
outline: 2px solid #063312; /* Depth */
outline-offset: 1px;
```

**Input (Error)**
```css
border-color: #ED6767; /* Coral Bold */
outline: 2px solid #ED6767; /* Coral Bold */
```

**Input Placeholder**
```css
color: #7B847B; /* Stone */
```

### Badges & Tags

**Success**
```css
background: #B5F5B7; /* Ease */
color: #063312; /* Depth */
border: 1px solid #61DB6B; /* Pulse – verhindert Verschwimmen auf Halo */
```

**Error**
```css
background: #FFD2D2; /* Coral Light */
color: #063312; /* Depth */
border: 1px solid #ED6767; /* Coral Bold */
```

**Warning**
```css
background: #FFF4D0; /* Solea Light */
color: #063312; /* Depth */
border: 1px solid #FFDB76; /* Solea Bold */
```

**Info**
```css
background: #C1E2F1; /* Aeris Light */
color: #063312; /* Depth */
border: 1px solid #52B4D9; /* Aeris Bold */
```

**Neutral (Standard-Tag)**
```css
background: #DEECDC; /* Mist */
color: #063312; /* Depth */
border: 1px solid #AFCAAF; /* Sage */
```

---

## Dark Mode

Wenn auf dunklem Hintergrund (Shade `#0B1E0F`) gearbeitet wird, gelten folgende Zuweisungen:

### Farbmapping Light → Dark

| Rolle | Light Mode | Dark Mode |
|-------|-----------|-----------|
| **Hintergrund (Seite)** | Halo `#F2F4F2` | Shade `#0B1E0F` |
| **Hintergrund (Container)** | Mist `#DEECDC` | Grove `#172D1B` |
| **Textfarbe (primär)** | Depth `#063312` | Halo `#F2F4F2` |
| **Textfarbe (sekundär)** | Root `#454F45` | Sage `#AFCAAF` |
| **Textfarbe (tertiär)** | Stone `#7B847B` | Stone `#7B847B` |
| **Borders** | Sage `#AFCAAF` | Root `#454F45` |
| **Input Border** | Stone `#7B847B` | Stone `#7B847B` |
| **Input Background** | Halo `#F2F4F2` | Shade `#0B1E0F` |
| **Card Background** | Halo `#F2F4F2` | Grove `#172D1B` |
| **Card Border** | Sage `#AFCAAF` | Root `#454F45` |
| **Primary Button BG** | Depth `#063312` | Halo `#F2F4F2` |
| **Primary Button Text** | Halo `#F2F4F2` | Depth `#063312` |
| **Accent Button BG** | Pulse `#61DB6B` | Pulse `#61DB6B` |
| **Accent Button Text** | Depth `#063312` | Depth `#063312` |
| **Link** | Aeris Bold `#52B4D9` | Aeris Standard `#ACD6EF` |
| **Logo** | Depth `#063312` | Bloom `#92EF9A` |

### Prinzip

Die Neutral-Skala wird im Dark Mode umgekehrt: Was im Light Mode dunkel ist (Depth, Root), wird im Dark Mode für helle Elemente verwendet – und umgekehrt. Der Primary Button invertiert ebenfalls (Depth-BG → Halo-BG). Nur der Accent Button (Pulse) bleibt in beiden Modi identisch, da Depth-Text auf Pulse universell funktioniert.

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

## Accessibility

### Kontrast-Anforderungen

**Light Mode (auf Halo #F2F4F2)**

| Kombination | Kontrast | WCAG | Verwendung |
|-------------|----------|------|------------|
| Depth auf Halo | 12.5:1 | AAA | Primärtext, Überschriften |
| Root auf Halo | 6.1:1 | AA | Sekundärtext |
| Stone auf Halo | 3.8:1 | AA large | Nur Tertiärtext, Placeholder (min. 16px) |
| Halo auf Depth | 12.5:1 | AAA | Primary Button Text |
| Depth auf Pulse | 7.1:1 | AAA | Accent Button Text |
| Aeris Bold auf Halo | 3.6:1 | AA large | Links (min. 16px, mit Underline) |

**Dark Mode (auf Shade #0B1E0F)**

| Kombination | Kontrast | WCAG | Verwendung |
|-------------|----------|------|------------|
| Halo auf Shade | 14.8:1 | AAA | Primärtext |
| Bloom auf Shade | 8.2:1 | AAA | Logo, Akzente |
| Sage auf Shade | 5.4:1 | AA | Sekundärtext |
| Aeris Std auf Shade | 7.9:1 | AAA | Links |

**Problematische Kombinationen (NICHT verwenden)**

| Kombination | Kontrast | Problem |
|-------------|----------|---------|
| Ease auf Halo | 1.4:1 | Unlesbar – Ease nur mit Border verwenden |
| Veil auf Halo | 1.3:1 | Kaum sichtbar – nicht als alleiniger Kontrast |
| Stone auf Shade | 2.8:1 | Zu wenig – im Dark Mode Sage statt Stone |
| Pulse auf Halo | 2.2:1 | Button-Fläche schwer erkennbar – Border nötig |

### Fokus-States
```css
outline: 2px solid #063312; /* Depth – dezent und professionell */
outline-offset: 1px;
```

### Mindest-Kontrastwerte
- **Normaler Text:** mindestens 4.5:1 (AA)
- **Grosser Text (ab 18px bold / 24px regular):** mindestens 3:1
- **UI-Elemente und Borders:** mindestens 3:1 gegen Hintergrund

---

## Quick Reference für KI

```
PRIMÄRFARBEN:
- Text/Logo hell: #063312 (Depth)
- Hintergrund hell: #F2F4F2 (Halo)
- Logo dunkel: #92EF9A (Bloom)
- Hintergrund dunkel: #0B1E0F (Shade)

INTERAKTIV:
- Primary Button: #063312 (Depth) mit #F2F4F2 (Halo) Text – DER Standard
- Accent Button: #61DB6B (Pulse) mit #063312 (Depth) Text – max. 1x pro Bereich
- Secondary: transparent mit #AFCAAF (Sage) Border
- Ghost: nur Text in #454F45 (Root), kein Border
- Danger: #ED6767 (Coral Bold) mit #F2F4F2 (Halo) Text
- Links: #52B4D9 (Aeris Bold), auf dunkel: #ACD6EF (Aeris Std)
- Focus: #063312 (Depth) Outline, NICHT Pulse

FEEDBACK:
- Success: #B5F5B7 (Ease) + #61DB6B (Pulse) Border
- Error: #FFD2D2 (Coral Light) + #ED6767 (Coral Bold) Border
- Warning: #FFF4D0 (Solea Light) + #FFDB76 (Solea Bold) Border
- Info: #C1E2F1 (Aeris Light) + #52B4D9 (Aeris Bold) Border

NEUTRAL (hell → dunkel):
#F2F4F2 → #DEECDC → #D1E2D1 → #AFCAAF → #7B847B → #454F45

DARK MODE:
- Hintergrund: #0B1E0F (Shade), Container: #172D1B (Grove)
- Text: #F2F4F2 (Halo), Sekundär: #AFCAAF (Sage)
- Borders: #454F45 (Root), Inputs: #7B847B (Stone)
- Primary Button: #F2F4F2 (Halo) BG mit #063312 (Depth) Text (invertiert!)
- Accent Button: #61DB6B (Pulse) bleibt gleich

FONTS:
- Regular: TWKLausanne-300
- Bold: TWKLausanne-600

LOGOS (wichtigste):
- Light: assets/logos/N-Depth-Halo.svg
- Dark: assets/logos/N-Bloom.svg
- Wortmarke: assets/logos/Notioneers-Depth-Halo.svg

ICONS:
- 31 Icons in 4 Varianten (depth, mist, mist-round, transparent)
- Pfad: assets/icons/{variante}/{name}.svg

NICHT KOMBINIEREN:
- Ease auf Halo ohne Border (1.4:1)
- Veil auf Halo ohne Border (1.3:1)
- Stone auf Shade (2.8:1)
```

---

*Version 2.0 – Notioneers Brand Library*
