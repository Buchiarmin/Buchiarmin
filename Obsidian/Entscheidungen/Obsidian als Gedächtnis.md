---
date: 2026-11-03
tags: [entscheidung, vorliebe]
---
# Obsidian als Gedächtnis

**Wunsch des Nutzers:** Claude soll immer alles in Obsidian schreiben und Obsidian als Gedächtnis nehmen.

**Umsetzung:**
- Regel steht in `CLAUDE.md` im Repo-Root, die Claude Code automatisch in jeder Sitzung lädt.
- Vault ist der Ordner `Obsidian/` in diesem Repo, synchronisiert über Git. So ist er in Cloud- und lokalen Sitzungen gleich.
- In Obsidian: diesen Ordner als Vault öffnen; mit dem Community-Plugin „Obsidian Git“ automatisch pullen/pushen.

Siehe [[Index]].
