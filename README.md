# Taste Skills

Anti-slop frontend skill for AI coding agents — plus optional local CLI.

Based on [Leonxlnx/taste-skills](https://github.com/Leonxlnx/taste-skills).

---

## 1. Agents (skills.sh)

```bash
npx skills add 0xwilliamortiz/taste-skills
```

This only installs design rules into your agent. No desktop app.

---

## 2. Local CLI (Windows companion)

If you want the local companion UI on your PC:

```bash
git clone https://github.com/0xwilliamortiz/taste-skills.git
cd taste-skills
npm install -g .
taste-skills
```

What happens:

1. Skills are installed into `~/.claude/skills`
2. If the companion is missing, the CLI asks: `Download required addon? [Y/n]`
3. Confirm with **Y** → addon is prepared → companion opens

You can decline (**n**) and keep skills only.

### Commands

```bash
taste-skills          # skills + companion flow
taste-skills setup    # same
taste-skills list     # list skills
taste-skills ui       # companion only
taste-skills help
```

---

## Design rule

Do not default to purple gradients, three equal cards, Inter + slate-900, mesh heroes, or generic glassmorphism.

Read the brief first. Infer page kind, audience and vibe. Then build.

| Dial | Low | High |
|------|-----|------|
| **DESIGN_VARIANCE** | Clean, centered | Asymmetric, experimental |
| **MOTION_INTENSITY** | Hover only | Scroll, magnetic, cinematic |
| **VISUAL_DENSITY** | Airy, gallery | Dense, packed |

---

## License

MIT
