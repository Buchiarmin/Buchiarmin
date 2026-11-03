---
date: 2026-11-03
tags: [projekt, obsidian, mobil]
---
# Obsidian am Handy

Vault liegt auf GitHub (privates Repo `Buchiarmin/claude-setup`), Notizen im Ordner `Obsidian/`.

**Einrichtung am Handy:**
1. Beim Start „Auf diesem Gerät“ wählen (nicht Obsidian Sync/iCloud – die verbinden nicht mit GitHub), leeren Vault `claude-setup` anlegen.
2. Community-Plugin „Git“ (Vinzent) installieren und aktivieren.
3. GitHub Fine-grained Token: nur Repo `claude-setup`, Contents: Read and write.
4. In Obsidian unter Git → Authentication: Benutzer `Buchiarmin` + Token.
5. Befehl „Git: Clone an existing remote repo“ → `https://github.com/Buchiarmin/claude-setup.git`, Zielordner leer.
6. Später: „Git: Pull“ (Notizen holen), „Git: Commit and sync“ (hochladen).

Token nie in den Vault schreiben. Siehe [[Obsidian als Gedächtnis]].
