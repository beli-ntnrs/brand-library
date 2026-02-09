# CLAUDE.md

## Sync-Regel

Wenn `brand-guidelines.md` geändert wird, muss `brand-guidelines-notion.md` ebenfalls aktualisiert werden, damit beide Dateien synchron bleiben.

**brand-guidelines.md** ist die Source of Truth. Die Notion-Version ist eine vereinfachte Ableitung davon.

### Unterschiede zwischen den Dateien

| | brand-guidelines.md | brand-guidelines-notion.md |
|---|---|---|
| **Zielgruppe** | KI-Systeme, Entwickler | Notion (Copy-Paste) |
| **CSS-Codeblöcke** | Ja (vollständige CSS) | Nein (alles in Tabellen) |
| **Quick Reference** | Ja (Codeblock für Prompts) | Nein |
| **Font-Pfade** | Ja (Dateipfade) | Nein |
| **Detailgrad** | Maximal | Vereinfacht, übersichtlich |

### Workflow

1. Änderung in `brand-guidelines.md` vornehmen
2. Dieselbe Änderung in `brand-guidelines-notion.md` übertragen (Notion-Format beachten)
3. Beide Dateien zusammen committen
