<div align="center">

# Hi, I'm Robson 👋

Developer focused on **automation and performance** · scripts, bots, CTF writeups and open-source tools · Brazil 🇧🇷

[niedson.com](https://niedson.com) · [g01x5.com.br](https://g01x5.com.br)

</div>

---

## 🎬 Featured: Higgsfield Director PRO

<a href="https://github.com/rniedson/higgsfield-director-pro-skill">
  <img src="https://raw.githubusercontent.com/rniedson/higgsfield-director-pro-skill/main/docs/assets/social-preview.png" alt="Higgsfield Director PRO: cinematic direction skill for AI-generated video" width="100%">
</a>

<div align="center">

[![Release](https://img.shields.io/github/v/release/rniedson/higgsfield-director-pro-skill?color=bca271&label=release)](https://github.com/rniedson/higgsfield-director-pro-skill/releases/latest)
[![Tests](https://github.com/rniedson/higgsfield-director-pro-skill/actions/workflows/testes.yml/badge.svg)](https://github.com/rniedson/higgsfield-director-pro-skill/actions/workflows/testes.yml)
![Tested in Claude Code](https://img.shields.io/badge/tested%20in-Claude%20Code-bca271)
![Python](https://img.shields.io/badge/python-3.9%2B-3776AB)
[![License: MIT](https://img.shields.io/badge/code-MIT-blue)](https://github.com/rniedson/higgsfield-director-pro-skill/blob/main/LICENSE)

</div>

An **agent skill** that turns a creative brief into well-directed AI-generated shots on Higgsfield. It picks the model
from the live catalog, writes one prompt per shot, keeps characters and products consistent across shots, prices the
job in credits and **stops for your "ok" before a single credit is spent**.

| <img src="https://raw.githubusercontent.com/rniedson/higgsfield-director-pro-skill/main/docs/manual/visual/assets/GIF001.gif" width="140" alt="Dolly in"><br>**Dolly in** | <img src="https://raw.githubusercontent.com/rniedson/higgsfield-director-pro-skill/main/docs/manual/visual/assets/GIF009.gif" width="140" alt="Pan left"><br>**Pan left** | <img src="https://raw.githubusercontent.com/rniedson/higgsfield-director-pro-skill/main/docs/manual/visual/assets/GIF005.gif" width="140" alt="Orbit clockwise"><br>**Orbit** | <img src="https://raw.githubusercontent.com/rniedson/higgsfield-director-pro-skill/main/docs/manual/visual/assets/GIF007.gif" width="140" alt="Crane up"><br>**Crane up** |
|:---:|:---:|:---:|:---:|

- **Cost gate:** quotes from the Higgsfield connector, then a hard stop until the operator approves that total.
- **Live model catalog:** limits checked against the catalog, with a dated 122-model snapshot for offline work.
- **`hfd.py`:** validates continuity, the 180° rule and model limits; compiles prompts; budgets from real quotes.
  Python standard library only, no network.
- **Illustrated manual:** 11 parts and 185 schematic images on camera, light, optics, color and continuity.
- **Engineering:** 51 tests in CI on Python 3.9 to 3.13, CodeQL, Dependabot and a security policy.

```bash
git clone https://github.com/rniedson/higgsfield-director-pro-skill.git
ln -s "$PWD/higgsfield-director-pro-skill/higgsfield-director" ~/.claude/skills/higgsfield-director
```

**[Read the README](https://github.com/rniedson/higgsfield-director-pro-skill#readme)** · [Illustrated manual](https://github.com/rniedson/higgsfield-director-pro-skill/blob/main/docs/manual/README.md) ·
[Discussions](https://github.com/rniedson/higgsfield-director-pro-skill/discussions) · [Changelog](https://github.com/rniedson/higgsfield-director-pro-skill/blob/main/CHANGELOG.md)

<sub>Independent project, not affiliated with or endorsed by Higgsfield.</sub>

---

## 🛠️ Other work

| Project | What it is |
|---|---|
| [writeups_ctf](https://github.com/rniedson/writeups_ctf) | CTF writeups site built with Astro, in Portuguese, Spanish and English |
| [flagyard](https://github.com/rniedson/flagyard) | Writeups, solve scripts and tooling for the FlagYard training labs |
