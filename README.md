# Meine Claude Code Skills/Plugins

Dieses Repo enthält in `.claude/settings.json` alle Marketplaces und Plugins unten.
Wer Claude Code in diesem Ordner startet und dem Ordner vertraut, bekommt sie automatisch zur Installation angeboten.

Manuell (in Claude Code eingeben): erst Marketplace hinzufügen, dann Plugin installieren.
Der offizielle Marketplace `claude-plugins-official` ist schon eingebaut.

| # | Plugin | Wofür | Quelle |
|---|--------|-------|--------|
| 1 | Superpowers | Brainstorming, Planen, Debugging, TDD, Code-Review-Workflows | https://github.com/obra/superpowers |
| 2 | Frontend Design | UI mit eigenem Stil statt Standard-Look (offiziell) | https://github.com/anthropics/claude-plugins-official |
| 3 | Code Review | PR-Reviews (offiziell) | https://github.com/anthropics/claude-plugins-official |
| 4 | Marketing Skills | CRO, Copywriting, SEO, Ads, E-Mails, Pricing, Launch … | https://github.com/coreyhaines31/marketingskills |
| 5 | Taste Skill | Bessere Frontend-Ästhetik: minimalistisch, brutalistisch, Redesign … | https://github.com/Leonxlnx/taste-skill |
| 6 | Caveman | Kurze, knappe Antworten, spart Tokens | https://github.com/JuliusBrussee/caveman |
| 7 | Claude SEO | SEO-Audits, Local SEO, Schema, Sitemaps … | https://github.com/AgriciDaniel/claude-seo |
| 8 | Claude Ads | Audits für Google, Meta, TikTok, LinkedIn Ads usw. | https://github.com/AgriciDaniel/claude-ads |
| 9 | UI/UX Pro Max | Design-Datenbank (Styles, Paletten, Fonts) + banner-design, brand, design, design-system, slides, ui-styling | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill |

```
/plugin install superpowers@claude-plugins-official
/plugin install frontend-design@claude-plugins-official
/plugin install code-review@claude-plugins-official

/plugin marketplace add coreyhaines31/marketingskills
/plugin install marketing-skills@marketingskills

/plugin marketplace add Leonxlnx/taste-skill
/plugin install taste-skill@taste-skill

/plugin marketplace add JuliusBrussee/caveman
/plugin install caveman@caveman

/plugin marketplace add AgriciDaniel/claude-seo
/plugin install claude-seo@agricidaniel-claude-seo

/plugin marketplace add AgriciDaniel/claude-ads
/plugin install claude-ads@ai-marketing-hub-claude-ads

/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

Danach `/reload-plugins` ausführen oder Claude Code neu starten.
