# Notioneers UI Guidelines

> UI-Komponenten für Notioneers. Farben, Fonts und Logos: → brand-guidelines.md

---

## Designprinzip

Die UI ist minimalistisch und professionell. Neutrale Farben dominieren. Pulse wird sparsam eingesetzt – nur dort, wo eine Aktion Aufmerksamkeit erfordert.

---

## Buttons

| Typ | Hintergrund | Text | Border | Wann |
| --- | --- | --- | --- | --- |
| **Primary** | Depth #063312 | Halo #F2F4F2 | Depth #063312 | Standard – der häufigste Button |
| **Accent** | Pulse #61DB6B | Depth #063312 | Depth #063312 | Sparsam – max. 1 CTA pro Bereich |
| **Secondary** | transparent | Depth #063312 | Sage #AFCAAF | Nebenaktionen |
| **Ghost** | transparent | Root #454F45 | keine | Tertiäre Aktionen |
| **Danger** | Coral Bold #ED6767 | Halo #F2F4F2 | Coral Bold #ED6767 | Löschaktionen |
| **Disabled** | #BCC9BC | Root #454F45 | #BCC9BC | Inaktive Buttons |

**Hover-States:**

| Typ | Hintergrund | Text |
| --- | --- | --- |
| Primary → | Pulse #61DB6B | Depth #063312 |
| Accent → | Depth #063312 | Halo #F2F4F2 |
| Secondary → | Veil #D1E2D1 | Depth #063312 |
| Ghost → | Mist #DEECDC | Depth #063312 |
| Danger → | Depth #063312 | Coral Bold #ED6767 |

**Hierarchie:**

- Seite mit klarer Hauptaktion: Accent + Secondary + Ghost
- Seite ohne klare Hauptaktion: Primary + Secondary + Ghost
- Maximal EIN Accent Button pro sichtbarem Bereich

**Alle Buttons: font-weight 300 (nie bold), border-radius 8px, padding 12px 24px**

---

## Links

| Zustand | Farbe |
| --- | --- |
| Standard | Aeris Bold #52B4D9 (mit Underline) |
| Hover | Depth #063312 |
| Auf dunklem Hintergrund | Aeris Standard #ACD6EF |

---

## Cards

- Hintergrund: Halo #F2F4F2
- Border: 1px Sage #AFCAAF
- Border-Radius: 12px
- Padding: 24px

---

## Input Fields

| Zustand | Border | Hintergrund |
| --- | --- | --- |
| Standard | Stone #7B847B | Halo #F2F4F2 |
| Focus | Depth #063312 | Halo #F2F4F2 |
| Error | Coral Bold #ED6767 | Halo #F2F4F2 |
| Placeholder-Text | Stone #7B847B | – |

**Border-Radius: 8px**

---

## Badges & Tags

| Typ | Hintergrund | Border | Text |
| --- | --- | --- | --- |
| **Success** | Ease #B5F5B7 | Pulse #61DB6B | Depth #063312 |
| **Error** | Coral Light #FFD2D2 | Coral Bold #ED6767 | Depth #063312 |
| **Warning** | Solea Light #FFF4D0 | Solea Bold #FFDB76 | Depth #063312 |
| **Info** | Aeris Light #C1E2F1 | Aeris Bold #52B4D9 | Depth #063312 |
| **Neutral** | Mist #DEECDC | Sage #AFCAAF | Depth #063312 |

---

## Dark Mode

| Rolle | Light Mode | Dark Mode |
| --- | --- | --- |
| Hintergrund (Seite) | Halo #F2F4F2 | Shade #0B1E0F |
| Hintergrund (Container) | Mist #DEECDC | Grove #172D1B |
| Text (primär) | Depth #063312 | Halo #F2F4F2 |
| Text (sekundär) | Root #454F45 | Sage #AFCAAF |
| Borders | Sage #AFCAAF | Root #454F45 |
| Input Border | Stone #7B847B | Stone #7B847B |
| Card Background | Halo #F2F4F2 | Grove #172D1B |
| Primary Button BG | Depth #063312 | Halo #F2F4F2 |
| Primary Button Text | Halo #F2F4F2 | Depth #063312 |
| Accent Button | Pulse #61DB6B | Pulse #61DB6B (gleich) |
| Link | Aeris Bold #52B4D9 | Aeris Std #ACD6EF |
| Logo | Depth #063312 | Bloom #92EF9A |

**Prinzip:** Neutrale Skala wird umgekehrt. Primary Button invertiert. Accent Button (Pulse) bleibt gleich.

---

## Accessibility

### Kontrast Light Mode (auf Halo)

| Kombination | Kontrast | WCAG |
| --- | --- | --- |
| Depth auf Halo | 12.5:1 | AAA |
| Root auf Halo | 6.1:1 | AA |
| Stone auf Halo | 3.8:1 | AA (nur gross) |
| Halo auf Depth | 12.5:1 | AAA |
| Depth auf Pulse | 7.1:1 | AAA |

### Kontrast Dark Mode (auf Shade)

| Kombination | Kontrast | WCAG |
| --- | --- | --- |
| Halo auf Shade | 14.8:1 | AAA |
| Bloom auf Shade | 8.2:1 | AAA |
| Sage auf Shade | 5.4:1 | AA |

### Nicht verwenden

| Kombination | Kontrast | Problem |
| --- | --- | --- |
| Ease auf Halo | 1.4:1 | Nur mit Border verwenden |
| Veil auf Halo | 1.3:1 | Nicht als alleiniger Kontrast |
| Stone auf Shade | 2.8:1 | Im Dark Mode Sage verwenden |
| Pulse auf Halo | 2.2:1 | Button braucht Border |

---

*Version 2.1 – Notioneers UI Guidelines*
*Visuelle Vorschau: ui-preview.html*
