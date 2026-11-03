# Regeln für Claude

## Obsidian ist dein Gedächtnis – IMMER

Der Ordner `Obsidian/` in diesem Repo ist ein Obsidian-Vault und dein Langzeitgedächtnis.

**Zu Beginn jeder Aufgabe:**
1. `Obsidian/Index.md` lesen.
2. Die dort verlinkten Notizen lesen, die zur Aufgabe passen. Was dort steht, gilt als bekannt; frag nicht erneut danach.

**Während und am Ende jeder Aufgabe – alles in Obsidian schreiben:**
- Ergebnisse, Entscheidungen, Vorlieben des Nutzers, offene Punkte und nächste Schritte als Markdown-Notizen festhalten.
- Ablage:
  - `Obsidian/Projekte/` – eine Notiz pro Projekt/Thema
  - `Obsidian/Entscheidungen/` – getroffene Entscheidungen mit Begründung
  - `Obsidian/Sessions/JJJJ-MM-TT – Thema.md` – kurzes Protokoll jeder Sitzung
- Jede Notiz bekommt Frontmatter (`date`, `tags`) und verlinkt verwandte Notizen mit `[[Wikilinks]]`.
- Neue Notizen in `Obsidian/Index.md` eintragen.
- **Dicht vernetzen (Graph-Ansicht soll wie ein großes Netz aussehen):** Für jedes wichtige Thema, Werkzeug, Begriff oder jede Person eine eigene kurze Notiz in `Obsidian/Begriffe/` anlegen und überall, wo es vorkommt, per `[[Wikilink]]` verlinken – auch zwischen Projekten, Entscheidungen und Sessions. Lieber ein Link zu viel als zu wenig.
- Bestehende Notizen aktualisieren statt Duplikate anzulegen.
- Nichts Geheimes (Passwörter, API-Keys, Tokens) in den Vault schreiben.
- Notizen auf Deutsch.
- Dem Nutzer einfach und ohne Fachbegriffe erklären; Schritt für Schritt, einen Schritt pro Nachricht, wenn er etwas selbst tun muss.

Die Vault-Änderungen werden zusammen mit der restlichen Arbeit committet und gepusht, damit das Gedächtnis in jeder Sitzung (Cloud und lokal) verfügbar ist.
