# Reference-free transfer checks

These checks evaluate whether an agent applies the Style's judgment to a new brief. They do not prove model training, guarantee every agent's quality, or measure visual similarity to the source corpus. Use the full specification and worked examples as the standard.

## Hard gates before polish

Any failure below requires repair or explicit disclosure of a verification limitation. A high craft score cannot cancel it.

| Gate | Inspectable failure | Required response |
|---|---|---|
| Evidence integrity | Invented source, unsupported outcome, causality from correlation, forecast labeled actual | Correct the claim, label uncertainty, or remove it |
| Data integrity | Different bases disguised as a funnel, distorted bar scale, inconsistent unit/period, unreconciled total | Repair the encoding or calculation and its interpretation |
| Essential readability | Critical text, labels, units, or qualifications unreadable in the intended mode | Edit, enlarge, recrop, or decompose |
| Complete content | Clipped text, broken accents, missing required decision, caption detached from evidence | Fix and rerender the affected pages |
| Provenance | Teaching facts or copied reference assets presented as the client's research | Replace with authorized inputs and appropriate labels |

## Anchored review rubric

Use 0 = fails, 1 = partly works, 2 = works. For each rating, name an observable defect or reason. This is a practical review aid, not an empirically validated measurement. Do not approve an average score while a required dimension remains unresolved.

| Dimension | 0: fails | 1: partly works | 2: works |
|---|---|---|---|
| Argument | Topic with no supported conclusion | Conclusion exists but evidence or scope is unclear | A bounded takeaway answers the audience question |
| First-glance hierarchy | Several competing entry points | One leads but a badge/image competes | One dominant object and clearly subordinate support |
| Spatial relationship | Interchangeable cards obscure meaning | Relationship requires prose to discover | Comparison, sequence, tension, or proof is visible |
| Selection and density | Relevant detail buried or essential support omitted | Readable but carries avoidable duplication | Enough for the decision; detail deliberately placed elsewhere |
| Type and spacing | Equal-weight roles, cramped groups, broken lines | Mostly clear with inconsistent exceptions | Stable roles, deliberate line breaks, meaningful group spacing |
| Image judgment | Generic, misleading, illegible, or poorly cropped | Relevant but scale/crop weakens the claim | Subject, action, and framing serve the argument |
| Concrete marketing logic | Slogan/channel list with no audience behavior | Some mechanism or brand role missing | Need, credible response, behavior, and intended outcome connect |
| Restraint and emphasis | Many unrelated accents and containers | Some decoration competes | Every prominent object earns its weight |
| Deck continuity | Topics and densities repeat without purpose | Local clarity with weak transitions | Headline logic and visual rhythm carry the decision |

If no image is warranted, evaluate the decision to omit it rather than forcing an image. Evaluate relevant dimensions at slide level and continuity at deck level. Inspect thumbnails for hierarchy, actual viewing size for reading, and close detail for correctness.

## Four unfamiliar practice briefs

Run these with the Style documents but without the original PDF. Request contracts and semantic composition plans first; ask for slide creation only when that is actually the task. No fixed layout is the correct answer.

### A. Evidence with an inconvenient result

**Fictional inputs.** A pilot has 500 sign-ups and 25 first purchases, against a target of 40. Spending is below the cap. Returns are not yet measured. A sponsor wants the title “A successful conversion engine.”

**Expected judgment.** Show the actual result against target, retain the definition of first purchase, distinguish low spending from success, and disclose unknown returns. A 5% sign-up-to-first-purchase rate is calculable for this cohort; it does not prove incremental sales. Rewrite or qualify the sponsor's claim and recommend the next investigation.

**Failure signal.** Oversized sign-ups and positive badges conceal the missed target or unknown quality of sales. The agent uses the worked examples' awareness numbers instead of the supplied cohort.

**Mutation.** Add a verified 8% baseline for a comparable cohort. The agent should incorporate the benchmark and reconsider the implication rather than merely append a small footnote.

### B. No photography and longer language

**Fictional inputs.** A Vietnamese read-ahead proposal needs to explain a return-service process. There are no authorized product photos. It has four actual stages and two exception routes; the legal qualification is material.

**Expected judgment.** Use a readable process representation, retain exception routes and the qualification, verify accents and line wrapping, and adjust density for read-ahead. A second page is acceptable when exceptions need independent explanation. The same typography and emphasis grammar applies without photos.

**Failure signal.** Fabricated photography, forced three-stage flow, tiny qualification, or decorative icons instead of actual process labels.

**Mutation.** Change delivery to a live five-minute presentation. The agent should simplify the main explanation and preserve accessible exception detail elsewhere, without deleting conditions.

### C. Purchaser and user differ

**Fictional inputs.** A purchaser values predictable cost; the end user values ease of handling. Each observation has a different research source. A verified feature helps handling, while cost predictability depends on a proposed subscription.

**Expected judgment.** Keep the two roles and sources distinguishable; connect the verified feature to use and label the subscription as proposed. Select imagery, if available, for the relevant role. One page or several may work if the relationship remains clear.

**Failure signal.** Merge both roles into a generic persona or imply that the product already provides the subscription benefit.

**Mutation.** Remove the subscription option. The agent must revise the brand role and claim rather than preserve the original benefit diagram.

### D. A hard slide limit with operational detail

**Fictional inputs.** A four-page approval deck has three phases, a cost cap, owners, two conditional gates, and thirty task lines. The audience needs a current commitment, not a task-by-task review.

**Expected judgment.** Select the approval narrative, preserve cap, accountability and gates, and place traceable tasks in notes or a separate supporting record if permitted. Explain any conflict if all thirty lines must be on-slide and readability cannot be preserved. Use four pages for four real questions, not four uniform grids.

**Failure signal.** Shrink everything to fit, omit an approval gate, or invent a new style for the operational page.

**Mutation.** Require a readable appendix as a separate artifact. The agent should link summary commitments to complete detail and check consistency across artifacts.

## Lightweight consistency evaluation

Give the same unfamiliar brief and all required documents to two independent runs. Keep brief, facts, delivery mode, and tool capability comparable. Different compositions can both pass. Compare supported takeaways, hierarchy, evidence distinctions, semantic consistency, and repair quality rather than pixel resemblance.

Then change one material constraint. Good transfer changes the affected claim, spatial relationship, density, or crop while preserving the shared system. If the result keeps the same geometry and ignores the changed premise, it has memorized an example instead of applying judgment.

Record: brief, files actually read, important choices, observed defects, repairs, and verification limits. A useful outcome is a concrete defect fixed; a generic “premium enough” assessment has little diagnostic value.

## Review record

```text
Audience / decision / delivery:
Documents fully read:
Evidence gaps and how claims were bounded:
Hard gates: pass / repair needed / unverified, with reasons
Strongest design decision and why:
Observed defect -> repair -> inspection result:
Constraint mutation -> changed decision:
Remaining limitations:
```

The source-disappearance test passes only when another agent can explain its decisions, adapt them to changed inputs, and produce a result that passes the relevant visual and evidence checks. Merely reciting the Style is insufficient.
