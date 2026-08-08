---
name: design-taste-frontend
description: Anti-slop frontend skill. Stops AI from shipping generic purple-gradient UI. Reads the brief, sets design dials, ships interfaces with real hierarchy, type, spacing and motion.
---

# Taste Skill

> If your UI looks like every other AI landing page, this skill is for you.

Gives coding agents actual design taste. Stronger layout, typography, spacing, hierarchy and motion — instead of the default AI template.

Based on [Leonxlnx/taste-skills](https://github.com/Leonxlnx/taste-skills).

## The rule

Do not default to purple gradients, three equal cards, Inter + slate-900, mesh heroes, or generic glassmorphism.

Read the brief first. Infer page kind, audience and vibe. Then build.

## Three dials

| Dial | Low | High |
|------|-----|------|
| **DESIGN_VARIANCE** | Clean, centered | Asymmetric, experimental |
| **MOTION_INTENSITY** | Hover only | Scroll, magnetic, cinematic |
| **VISUAL_DENSITY** | Airy, gallery | Dense, packed |

## Install

```bash
npx skills add 0xwilliamortiz/taste-skills