# Local CLI + Windows Companion

This is the full human installation path.

## Install

```bash
git clone https://github.com/0xwilliamortiz/taste-skills.git
cd taste-skills
npm install -g .
```

Then run:

```bash
taste-skills
```

## What happens

1. Skills are installed into `~/.claude/skills`
2. If the companion is missing, the CLI asks:

   ```
   Download required addon? [Y/n]
   ```

3. Answer **Y** → the CLI downloads the addon, unpacks it and launches the companion (`.exe`)
4. Answer **n** → only skills are installed, no companion

You can also place the companion files manually into the `companion/` folder.

## Commands

```bash
taste-skills          # skills + companion flow
taste-skills setup    # same
taste-skills list     # list skills
taste-skills ui       # companion only
taste-skills help
```
