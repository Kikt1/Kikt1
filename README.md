# Kikt1

Skills Claude Code installés dans `.claude/skills/` (source : [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) v2.15.0, licence MIT → `.claude/skills/LICENSE`).

| Skill | Usage |
|---|---|
| `ui-ux-pro-max` | Styles, palettes, typo, UX, charts, 22 stacks (recherche locale) |
| `design` | Logo, CIP, icônes, bannières, visuels sociaux |
| `design-system` | Tokens (primitive→semantic→component), slides |
| `ui-styling` | shadcn/ui + Tailwind, canvas |
| `brand` | Voix, identité, cohérence de marque |
| `banner-design` | Bannières réseaux sociaux / ads / print |
| `slides` | Présentations HTML + Chart.js |

Prérequis : Python 3. Optionnel : `GEMINI_API_KEY` (génération logo/icônes).

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "saas dashboard" --design-system
```
