---
name: stepwise-lab-notes
description: Organize existing wet-lab plans and rough notes into concise English procedures with explicit groups, aligned reagent quantities, and complete ordered steps. Use for protocol formatting, dilution and batch recalculation, or updating an existing lab procedure. Preserve experimental choices and the accepted layout; this is not an experimental-design or data-analysis skill.
---

# Stepwise Lab Notes

Turn an existing experimental plan into a clear procedure that the researcher can check and follow. Keep the purpose brief and every necessary operating step visible. Default to English procedures and concise replies in the user's language.

## Preserve the experiment

- Start from the latest user-provided record. Distinguish confirmed parameters, proposals, and actual observations.
- During formatting, preserve sample identities, sample order, conditions, reagent identities, quantities, and the operation sequence. Do not optimize or add experiments unless asked.
- Keep the complete workflow: dilution, initial preparation, instrument programs, subsequent mixes, additions, and readout. A reagent list is not a complete procedure.
- Preserve essential temperatures, durations, wash counts, centrifugation settings, mixing instructions, and instrument settings when supplied. Never infer missing parameters from a formatting example.
- If an omission or contradiction affects execution, identify the specific missing information. Do not fill it with a guess.

## Layout

Retain the user's accepted headings and order. For a new record, use only relevant sections:

1. **Title (YYYYMMDD)** — experiment name and date.
2. **Ob:** — one or two sentences describing the purpose and comparison.
3. **Result/Conclusion:** — optional; use Pending before results exist.
4. **Groups** — sample order, conditions, replicate count, and total wells or tubes. Specify what controls contain.
5. **Preparation** — stock-to-working dilutions and necessary pretreatment.
6. **Procedure** — numbered operations in actual execution order, with each recipe beside the step that uses it.
7. **Readout** — necessary settings and the planned comparison, preferably one line.

Do not force PCR, single-tube labels, or a fixed number of steps onto unrelated experiments. Avoid long introductions, repeated quantities, unnecessary warnings, and unsolicited troubleshooting. Do not extend a formatting request into result analysis or an archival system.

## Aligned recipes

Use short monospace text blocks rather than wide tables. Keep one reagent per line. Pad names with hyphens so single-reaction and batch quantities align vertically. Put units and the batch multiplier above the block.

Volumes: µL/tube (×8 total)

```text
Diluent -------- 7.0 (56.0)
Reagent A ------ 2.0 (16.0)
Reagent B ------ 1.0 ( 8.0)
```

This is a fictional formatting example, not an experimental recipe.

- Include stock information when supplied and operationally useful. Preserve reagent identifiers in private working records.
- Keep numeric precision sufficient for the experiment; do not round merely for appearance.
- Aim for short lines, roughly 40–55 characters. If a name is long, move supplementary information above the block rather than shrinking the font or truncating the identifier.
- Place volumes once, not in both prose and a duplicate table. Add final concentrations only when needed for interpretation or operation.
- Do not add nested toggles. Preserve an existing outer date container if the user uses one. Do not claim that toggles are expanded without checking the interface.

## Calculations and revisions

- Distinguish stock, working, intermediate-stage, and final reaction concentrations. State which volume defines a reported concentration.
- Check stage volumes, dilution factors, sample counts, replicates, and batch totals. Exclude separately added samples from shared master mixes.
- Use the user's batch-overage rule. Do not universally add three reactions or ten percent.
- Do not infer enzyme activity from volume, reinterpret concentration conventions, or equate a thermocycler's extra returns with total cycles.
- When conditions change, update only affected text and dependent calculations. Preserve all unrelated formatting and content.
- Keep planned work separate from historical execution and observations.

## Publishing and external records

- For public examples, replace project-specific names consistently with neutral labels. Do not include private project files, sequence identities, account paths, or an identity mapping. Preserve or anonymize numerical values according to the user's request.
- When editing an external record, read its current content, make a scoped change, and read it back. A truncated page response is not evidence of an empty section.
- If a write fails or returns uncertain status, inspect current state before retrying. Skill invocation alone does not authorize writing to external applications.
- Do not generate additional document formats or install the skill unless requested. Finish with a brief confirmation and the requested deliverable.

See [the generic template](references/template.md) when starting a new record. Adapt it to supplied information; never treat placeholders as instructions to execute an experiment.
