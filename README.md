# Sports Training & Nutrition Skills

Reusable AI-agent skills for practical strength training, periodization, recovery, and general sports nutrition. The shared guidance is paired with platform-specific installation files for Codex and Claude.

The material is based on a supplied Estonian sports-training guide and edited for public use. It is educational guidance, not medical advice. It deliberately avoids treating FMS cutoffs or ACWR ranges as stand-alone injury prediction tools, and avoids rigid nutrient-timing prescriptions.

## Contents

- `SKILL.md` — shared skill instructions
- `codex/SKILL.md` — Codex skill package entry point
- `claude/SKILL.md` — Claude skill package entry point
- `LICENSE` — MIT license

## Install

### Codex

Copy the `codex` directory into one of Codex's skill directories:

```text
# Current project only
.agents/skills/sports-training-nutrition/

# All projects for your user
~/.agents/skills/sports-training-nutrition/
```

The `codex/SKILL.md` is a complete standalone skill file.

### Claude Code

Copy the `claude` directory into either location:

```text
# Current project only
.claude/skills/sports-training-nutrition/

# All projects for your user
~/.claude/skills/sports-training-nutrition/
```

The `claude/SKILL.md` is a complete standalone skill file.

### claude.ai

Custom Skills on claude.ai are uploaded as ZIP files. Put `claude/SKILL.md` in a folder named `sports-training-nutrition`, zip that folder, then upload the ZIP from **Customize → Skills**. Skill availability depends on your plan and whether code execution is enabled.

## Source and editorial notes

The source was the user-provided Estonian guide *Sporditreeningu Periodiseerimise ja Jõuvõimete Arendamise Juhend AI-Agendile ja Skillile*. The skill retains its useful principles—individual intake, progressive strength training, periodization options, movement variety, warm-up, recovery, and sports nutrition—while adapting them for general public use.

In particular, it does not present the FMS score as an injury prediction or clearance test: systematic reviews find its predictive value insufficient or inconsistent ([BJSM review](https://bjsm.bmj.com/content/51/23/1661), [BMJ Open Sport & Exercise Medicine review](https://bmjopensem.bmj.com/content/5/1/e000501)). It also does not prescribe an ACWR “safe zone” as a validated automatic control rule. Protein guidance is framed as a flexible reference consistent with the ISSN position stand, with individual context noted ([ISSN](https://jissn.biomedcentral.com/articles/10.1186/s12970-017-0177-8)).

## Use

Ask for a plan or advice in natural language and provide the details that matter: goal, experience, schedule, equipment, preferences, and relevant constraints. The skill asks for missing information when it would materially change the recommendation.

## Scope and safety

The skill supports general training and nutrition education. It does not diagnose or treat illness or injury, replace a registered dietitian or clinician, or guarantee performance or injury outcomes. Users with significant symptoms or health constraints should seek individualized professional advice.

## Contributing

Open an issue or pull request with the proposed change and, for scientific claims, a primary or authoritative reference. Keep guidance cautious, practical, and clear about uncertainty.
