# CLAUDE.md

## Dateistruktur

| Datei | Inhalt | Notion-Version |
|---|---|---|
| `brand-guidelines.md` | Farben, Fonts, Logo, Icons, Tone of Voice | `brand-guidelines-notion.md` |
| `ui-guidelines.md` | Buttons, Cards, Inputs, Badges, Dark Mode, Accessibility | `ui-guidelines-notion.md` |
| `preview.html` | Visuelle Vorschau aller UI-Komponenten | – |

## Sync-Regeln

Jede Guideline-Datei hat eine Notion-Version. Beide müssen synchron bleiben.

**Source of Truth:** Die Markdown-Dateien (`brand-guidelines.md`, `ui-guidelines.md`). Die Notion-Versionen sind vereinfachte Ableitungen davon.

### Unterschiede Markdown → Notion

| | Markdown | Notion |
|---|---|---|
| **Zielgruppe** | KI-Systeme, Entwickler | Notion (Copy-Paste) |
| **CSS-Codeblöcke** | Ja (vollständige CSS) | Nein (alles in Tabellen) |
| **Quick Reference** | Ja (Codeblock für Prompts) | Nein |
| **Font-Pfade** | Ja (Dateipfade) | Nein |
| **Detailgrad** | Maximal | Vereinfacht, übersichtlich |

### Workflow

1. Änderung in der Markdown-Datei vornehmen
2. Dieselbe Änderung in die Notion-Version übertragen (Notion-Format beachten)
3. Beide Dateien zusammen committen
4. Falls UI-Komponenten geändert wurden: auch `preview.html` aktualisieren
