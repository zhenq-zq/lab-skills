---
name: stepwise-lab-notes
description: Write or update concise stepwise wet-lab protocols with one numbered condition per label, aligned quantities, forward-only execution and verified one-page A4 printing. Always use when the user says stepwise, stepwise lab note, 按步骤不要回头看, 按我的实验记录格式, or 按0921格式. Preserve experimental choices; not experimental design or data analysis.
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

## Short descriptions

- Use numbered lists (1, 2, 3...) for operations with a required execution order. Within each Step, number bench actions in execution order; reserve bullets for notes, conditions, cautions and interpretation. Never convert all operating instructions to bullets for visual consistency. Restart action numbering under each Step; keep notes distinct without creating extra actions.
- For groups, give every distinct condition one sequential number and one stable plot label in a single copyable plain-text block. Do not group number ranges or add well positions unless requested. The numbering identifies conditions, not execution order. Use bullets for other unordered facts.
- Apply this distinction throughout the record. Preserve explicit sample IDs as labels; do not imply that group listing order is an operating sequence.

- Default to one action or one fact per line throughout the procedure, including objectives, notes, and readouts.
- Keep each description short enough to fit one line in the normal document view; aim for roughly 40–55 English characters where practical.
- Split long sentences into separate short steps. Avoid explanatory paragraphs and repeated background.
- Preserve essential quantities, timing, temperatures, and sequence when shortening; move supporting conditions to their own short lines.
- Keep recipes in aligned monospace blocks. Do not force a line to fit by shrinking text or omitting necessary information.
- Screen widths vary: use short source lines, and check rendered wrapping when the interface is available.

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

## Shared mixes and preparation reserves

- For concentration screens, prepare identical compatible components together in one common master mix, then aliquot and add only the condition-specific reagent. Preserve any required separation or addition order from the approved protocol; do not combine chemically incompatible stages.
- If the user uses preassembled RNP, put its separate-tube Cas12a + gRNA recipe immediately before the consuming mix (for example Step 5a then 5b). Use confirmed stocks and assembly conditions; do not silently substitute a diluted RNP working solution or invent incubation settings.
- Use Plain Text monospace recipe blocks. After its recipe, label the downstream line simply RNP with aligned per-reaction and batch volumes. Avoid redundant prose repeating concentrations, totals and instructions already explicit in recipes. Do not reintroduce explanatory lines the user removed.
- Reserve volume at every preparation and transfer level: upstream RNP must exceed the amount consumed by the common batch; the common batch must exceed the sum of aliquots; each condition mix must exceed its well demand. Count serial-dilution withdrawals before checking working-solution reserves. Downstream overage alone does not provide upstream transfer reserve.
- Scale every common-mix component by the same factor, check totals and final concentrations, and retain the user's accepted reserve convention. Show one common recipe and a short copyable mapping of aliquot + condition-specific addition, rather than six repeated recipes.
- Example of volume accounting only: six 100 µL condition mixes for nine 10 µL additions each can use 80 µL common mix + 20 µL variable reagent per tube. A 528 µL common batch leaves 48 µL after six aliquots; if it consumes 26.4 µL RNP, a 32 µL RNP preparation leaves 5.6 µL. These numbers are illustrative, not a default experimental recipe.

## Forward execution and A4 printing

- Default lab-note print target is exactly one A4 portrait page (210 × 297 mm). Retain the accepted layout and ordered step labels; do not reorganize into tables or a new document design.
- Write steps in bench order. At the point of use state tube/reagent identity, working concentration, per-reaction and batch volumes, destination conditions, temperature/time and next action. Repeat short critical mappings when needed; avoid asking the reader to look back or open another record.
- Show unresolved execution-critical values as TBD before starting; never invent the selected concentration or call an incomplete plan ready to execute.
- Use monospace dash leaders; independently align single-reaction and batch amount columns, including Total. Avoid separate quote blocks with excessive spacing.
- When serial dilution is requested, list high-to-low preparation order, actual source tube/concentration, transfer and diluent volumes. Mix before every transfer. Account for downstream withdrawals and leave enough for the reaction mix plus the specified overage. Do not claim serial dilution necessarily improves accuracy; propagated errors remain possible.
- Initial A4 budget: about 450–650 English words and 65–80 rendered lines; line count and actual layout matter more than a hard word limit. Aim for 10–15 mm margins, 9–10 pt prose and 8–9 pt recipe text. Shorten repetition/empty space first, never remove essential experimental details or shrink to illegibility.
- Before claiming A4 readiness, render a print preview and verify one page, A4 dimensions, all numbered conditions, readable text, no clipped/wrapped quantities and aligned columns. Internal print QA is allowed for the requested one-page task; deliver PDF only when requested or useful as its preview.
- For Notion records, edit and verify Notion first. If the user requests review before sync, wait for confirmation before updating the local Markdown mirror. A PDF preview does not synchronize the record. Upon authorization synchronize the approved titles, group labels and content.

## River protocol compatibility

This is the single authoritative protocol-formatting skill. The old river-lab-protocol skill has been removed; use only stepwise-lab-notes.

- For existing River records preserve Ob, Result/Conclusion, Group arithmetic, exact sample IDs, reagent order, PCR/readout labels and the dated outer container. Use visible bold step labels; do not introduce nested toggles or wide tables.
- Preserve actual names such as Nuclease-free H₂O, HiFi Taq Ligase, Matching Mut Padlock and RCA primer IDs; keep sample addition separate from a common mix. Do not substitute a historical protocol's chemistry for the current approved recipe.
- Report stock, working and named-stage final concentrations distinctly. State enzyme stock-equivalent volume separately from diluted volume; do not infer enzyme units or dNTP each/total convention. Check every stage sum and batch quantity; retain the user's established overage.
- Formatting does not authorize new experimental conditions. A concentration screen alone does not validate an LOD. Keep interpretation out of the bench instructions unless requested.
- For Notion use the owning page and a narrow exact replacement, preserve unrelated blocks and nesting, read back all changed quantities and labels. Re-fetch after a failed/uncertain mutation; after two failed targeted attempts reassess instead of repeatedly editing. A block anchor is not necessarily a page ID.
- If the user says stepwise anywhere in a lab-note/protocol request, select this skill immediately. Do not substitute river-lab-protocol. Reply briefly in Chinese and link the updated destination when useful.

## Publishing and external records

- For public examples, replace project-specific names consistently with neutral labels. Do not include private project files, sequence identities, account paths, or an identity mapping. Preserve or anonymize numerical values according to the user's request.
- When editing an external record, read its current content, make a scoped change, and read it back. A truncated page response is not evidence of an empty section.
- If a write fails or returns uncertain status, inspect current state before retrying. Skill invocation alone does not authorize writing to external applications.
- Do not generate additional document formats or install the skill unless requested. Finish with a brief confirmation and the requested deliverable.

See [the generic template](references/template.md) when starting a new record. Adapt it to supplied information; never treat placeholders as instructions to execute an experiment.
