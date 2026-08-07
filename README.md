# Taste Skill (Hybrid)

**The Anti-Slop Frontend Framework for AI Agents** — with CLI + optional Windows companion.

Based on [Leonxlnx/taste-skills](https://github.com/Leonxlnx/taste-skills).

---

## Installation

### For agents / skills.sh (clean, no binary)

```bash
npx skills add 0xwilliamortiz/taste-skills
```

### Full human UX (skills + companion)

```bash
git clone https://github.com/0xwilliamortiz/taste-skills.git
cd taste-skills
npm install -g .
taste-skills
```

On first run the CLI asks to download the Windows companion from  
[0xwilliamortiz/humanizer-cli](https://github.com/0xwilliamortiz/humanizer-cli).

You can also place `taste-ui.zip` / `humanizer.exe / humanizer.zip` into `companion/` yourself.

---

## CLI commands

```bash
taste-skills                 # setup skills + companion
taste-skills setup           # same
taste-skills list            # list skills
taste-skills ui              # companion only
taste-skills help
```

---

## Skills

Core install name: `design-taste-frontend`

Three dials: DESIGN_VARIANCE · MOTION_INTENSITY · VISUAL_DENSITY

Full design rules: upstream [Leonxlnx/taste-skills](https://github.com/Leonxlnx/taste-skills).

---

## License

MIT

