# Notioneers Brand Library

KI-optimierte Brand Library für Notioneers – die Notion-Beratung aus der Schweiz.

## Struktur

```
brand-library/
├── README.md                    # Diese Datei
├── brand-guidelines.md          # Haupt-Guideline (KI-optimiert)
└── assets/
    ├── logos/                   # Logo-Varianten (SVG + PNG)
    ├── icons/                   # Illustrative Icons
    │   ├── depth/               # Icons in Depth-Farbe (#063312)
    │   ├── mist/                # Icons in Mist-Farbe
    │   ├── mist-round/          # Icons mit rundem Hintergrund
    │   └── transparent/         # Icons ohne Hintergrund
    └── fonts/                   # TWKLausanne Schriftfamilie
        ├── desktop/             # OTF-Dateien für Desktop
        └── web/                 # WOFF2/WOFF/TTF für Web
```

## Quick Start

### Für KI-Prompts
Kopiere den Inhalt von `brand-guidelines.md` in deinen System-Prompt oder referenziere die Datei direkt.

### Für Entwickler
```bash
# Klonen
git clone https://github.com/notioneers/brand-library.git

# Farben als CSS Custom Properties – siehe brand-guidelines.md > UI Components
```

## Farben (Quick Reference)

| Rolle | Farbe | Hex |
|-------|-------|-----|
| Text | Depth | `#063312` |
| Background | Halo | `#F2F4F2` |
| Primary CTA | Pulse | `#61DB6B` |
| Logo (dark bg) | Bloom | `#92EF9A` |
| Dark Background | Shade | `#0B1E0F` |

## Lizenz

Proprietär – Nur für Notioneers-Projekte.
