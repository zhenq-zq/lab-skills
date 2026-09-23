# Lab Skills

A growing collection of focused AI skills for laboratory workflows. Each skill lives in its own folder and can be used independently.

## Skill catalog

| Skill | Purpose | Entry point |
| --- | --- | --- |
| **Stepwise Lab Notes** | Turn existing experimental plans into concise, ordered procedures with explicit groups and aligned reagent quantities. | [SKILL.md](skills/stepwise-lab-notes/SKILL.md) |

## Stepwise Lab Notes

For researchers who want consistent, readable procedures without repeatedly explaining formatting preferences. It preserves the complete workflow—from preparation and dilution to instrument programs, later additions, and readout.

- A short purpose statement and explicit sample order.
- One reagent per line, with aligned single-reaction and batch quantities.
- Recipes next to the steps that use them.
- Focused revisions and dependent recalculation.
- No unsolicited experimental redesign or invented operating parameters.

### Install and use

**Codex:** copy `skills/stepwise-lab-notes` into your configured skills directory (commonly `~/.codex/skills/`), then invoke `$stepwise-lab-notes` with your existing notes.

**Other assistants:** if your application supports `SKILL.md` packages, import the complete skill folder using that application's supported mechanism. Otherwise, supply the file as instructions. WorkBuddy-specific installation has not been verified here.

Example request:

> Use Stepwise Lab Notes to organize these notes into an English procedure. Keep every step and sample order, align single and batch volumes, and only ask about information necessary to execute the plan.

See the [generic template](skills/stepwise-lab-notes/references/template.md). It contains placeholders, not a validated experimental protocol. Researchers must check experimental parameters and calculations before use.

## Adding future skills

```text
skills/
  stepwise-lab-notes/
    SKILL.md
    references/
      template.md
  next-skill/
    SKILL.md
```

Give each skill a distinct scope and a lowercase hyphenated folder name matching its frontmatter `name`. Add its purpose and link to the catalog. Include assets or scripts only when they help that skill; keep private laboratory records out of this repository.
