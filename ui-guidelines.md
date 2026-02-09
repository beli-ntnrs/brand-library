# Notioneers UI Guidelines

> **Für KI-Systeme und Entwickler:** Diese Guideline definiert die UI-Komponenten von Notioneers. Farben, Fonts und Logos findest du in `brand-guidelines.md`. Die visuelle Vorschau aller Komponenten liegt in `ui-preview.html`.

---

## Designprinzip

Die UI ist minimalistisch und professionell. Neutrale Farben (Depth, Halo, Stone, Sage) dominieren. Pulse und andere Akzentfarben werden sparsam und gezielt eingesetzt – nur dort, wo eine Aktion Aufmerksamkeit erfordert. Die meiste Fläche bleibt ruhig.

---

## Buttons

**Primary Button (Standard – der häufigste Button)**
```css
background: #063312; /* Depth */
color: #F2F4F2; /* Halo */
border: 1px solid #063312; /* Depth */
border-radius: 8px;
padding: 12px 24px;
font-weight: 300;
```

**Primary Button (Hover)**
```css
background: #61DB6B; /* Pulse */
color: #063312; /* Depth */
border-color: #61DB6B; /* Pulse */
```

**Accent Button (sparsam – nur für eine zentrale CTA pro Seite)**
```css
background: #61DB6B; /* Pulse */
color: #063312; /* Depth */
border: 1px solid #063312; /* Depth */
border-radius: 8px;
padding: 12px 24px;
font-weight: 300;
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
font-weight: 300;
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
font-weight: 300;
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
font-weight: 300;
```

**Danger Button (Hover)**
```css
background: #063312; /* Depth */
color: #ED6767; /* Coral Bold */
border-color: #ED6767; /* Coral Bold */
```

**Disabled Button**
```css
background: #BCC9BC;
color: #454F45; /* Root */
border: 1px solid #BCC9BC;
cursor: not-allowed;
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

---

## Links

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

---

## Cards

```css
background: #F2F4F2; /* Halo */
border: 1px solid #AFCAAF; /* Sage */
border-radius: 12px;
padding: 24px;
```

---

## Input Fields

```css
background: #F2F4F2; /* Halo */
border: 1px solid #7B847B; /* Stone – klar sichtbare Feldgrenze */
border-radius: 8px;
color: #063312; /* Depth */
```

**Input (Focus)**
```css
border-color: #063312; /* Depth – dezent, kein Pulse */
```

**Input (Error)**
```css
border-color: #ED6767; /* Coral Bold */
```

**Input Placeholder**
```css
color: #7B847B; /* Stone */
```

---

## Badges & Tags

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

*Version 2.1 – Notioneers UI Guidelines*
*Visuelle Vorschau: `ui-preview.html`*
