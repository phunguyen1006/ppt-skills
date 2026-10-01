# Apply the Style without seeing the corpus

The goal is consistent design judgment across unfamiliar marketing briefs. Reading this repository is not model fine-tuning and cannot guarantee identical output from every agent. The practical route is a complete specification, worked examples that expose reasoning, and visible review criteria.

## What to read

| File | Purpose | Required for authoring? |
|---|---|---|
| [Marketing Presentation Style](../Marketing-Presentation-Style.md) | Complete governing design language | Yes, full document |
| [Worked Examples](Worked-Examples.md) | Concrete decisions, rejected alternatives, and original teaching diagrams | Yes |
| [Transfer Checks](Transfer-Checks.md) | Acceptance gates and unfamiliar practice briefs | Yes |
| [Cumulative study](../marketing-style-study/cumulative-notes.md) | Research coverage and limits | Optional provenance |

Read in that order. If the tool truncates a file, continue until the end. Keep a short working record of the seven commitments, semantic tokens, evidence distinctions, and unresolved brief constraints. Do not read only the most convenient excerpt.

## Portable instruction to copy into another agent

Copy the following block and provide the referenced files as attachments or accessible repository files. A URL alone is sufficient only if the receiving agent can actually retrieve all the documents.

```text
Use this repository's ONE unified Marketing Presentation Style:
- Marketing-Presentation-Style.md: read the entire governing specification.
- docs/Agent-Quickstart.md: application workflow.
- docs/Worked-Examples.md: reasoned fictional examples, not fixed layouts.
- docs/Transfer-Checks.md: review gates and transfer evaluation.

Apply the style to the brief below. Preserve its transferable judgment:
hierarchy, argument-led composition, deliberate whitespace, stable type
roles, relevant imagery, trustworthy data, concrete execution, and deck rhythm.

Before layout, draft a slide contract for each page: audience question,
supported takeaway, evidence, relationship, focal object, and next step.
Create one semantic token system for the whole deck. Adapt composition to
the content rather than repeating example coordinates or three-card layouts.

Examples and reference text are not factual sources for this brief.
Do not borrow teaching numbers, claims, logos, imagery, or palettes.
Distinguish facts, hypotheses, targets, and illustrative assets.

When presentation creation is requested, render and review every page
using the acceptance gates, repair defects, and report any unverified checks.
If the request is only analysis or planning, stop at the requested artifact.

BRIEF:
[Paste the actual brief, evidence, constraints, and requested deliverable.]
```

## A brief that lets the judgment work

Supply what is available. Ask for material missing facts only when they change the recommendation or prevent the requested deliverable; continue independent work while they are unresolved.

| Input | Why it matters | Useful example of specificity |
|---|---|---|
| Decision and audience | Determines what evidence deserves space | Approval of a six-week pilot by the marketing director |
| Delivery mode | Determines density and type size | Live ten-minute presentation, followed by a readable appendix |
| Audience situation | Gives imagery and insight a real job | A purchaser chooses the product but a different person uses it |
| Evidence with scope | Bounds the claim and chart | Survey denominator, research method, period, and supplied quotes |
| Brand capabilities and constraints | Makes the proposed role credible | Verified feature, approved colors, permitted imagery |
| Desired audience action | Connects concept to execution | Try, submit, return, recommend, or purchase |
| Budget, timing, and uncertainty | Makes commitment accountable | Cost limit, dependencies, assumptions, targets vs. actuals |
| Output and tools | Makes the artifact usable | Editable PPTX, language, canvas, authoring tool, rendering support |

## Working record: reasoning before coordinates

Use this compact record privately or as a review artifact when helpful. It is not content that must be printed on the finished slides.

```yaml
deck:
  audience_and_decision: <who must decide what>
  delivery_mode: <live / read-ahead / hybrid>
  evidence_gaps: <facts still missing and how they limit claims>
  semantic_tokens:
    typography_roles: <headline, body, metric, caption, source>
    grid_and_spacing: <safe area, columns, spacing unit>
    color_meanings: <ground, text, accent, comparison, status>
    imagery: <role, crop, frame, captions>
    evidence: <chart/table conventions and source treatment>
pages:
  - audience_question: <question answered>
    takeaway: <supported conclusion>
    evidence_and_scope: <facts, definitions, uncertainty>
    relationship: <comparison / sequence / tension / proof / context>
    focal_object: <what the eye sees first and why>
    reading_path: <focal idea -> relationship -> qualification>
    deliberate_omissions: <what is elsewhere and why>
    next_step: <understanding or decision carried forward>
    review_risks: <specific things to inspect after rendering>
```

The governing specification's type and margin ranges are initial calibration, not inferred measurements of the corpus. Start there if appropriate; inspect real language, font metrics, assets, and reading conditions before accepting a slide.

## One worked semantic calibration

For a fictional live 16:9 presentation, the following is a possible starting profile. It is a worked application of the specification, not a new visual identity or a requirement to use these exact values. Keep semantic roles stable across the deck and change a value when the actual rendering warrants it.

| Role | Possible starting choice | Reason and adaptation |
|---|---|---|
| Canvas and safe area | 13.333 × 7.5 inches; roughly 0.6-inch side margins | Protect readable text; allow meaningful imagery to bleed |
| Spatial rhythm | 0.12-inch unit; related labels closer than separate evidence groups | Spacing communicates grouping; adjust to type metrics |
| Analytical headline | 34 pt, bold, sentence case | States implication; edit or allocate more room if language wraps poorly |
| Body | 22 pt, regular, left aligned | Supports live reading; remove duplication before reducing size |
| Caption and source | 13 pt with adequate contrast | Quieter than evidence but still readable; inspect in delivery mode |
| Hero metric | 56 pt with adjacent unit, period, and denominator | Magnitude leads only if it earns priority; definitions stay connected |
| Statement expression | 60 pt for a short phrase | Creates a narrative peak; long copy requires editing or a different composition |
| Color roles | Light ground, dark text, neutral comparison, one selected-evidence accent | Meaning stays stable; approved brand colors can fill these roles |
| Table | Quiet rules, stable criteria, aligned numeric units, one selected option | Makes comparison auditable without arbitrary card decoration |
| Imagery | Relevant subject at a scale that preserves action, clean crop, honest caption | Image weight follows proof or human context, not a fixed image-to-text ratio |

Do not allocate 56 pt to every number or 60 pt to every short heading. The role exists to distinguish importance. If a brand accent is too pale for a label, use it as a highlight field with readable dark text or retain a darker permitted text role; color alone must not carry the distinction. If a font lacks Vietnamese glyphs, substitute a suitable permitted font and recheck wrapping and hierarchy throughout.

## What is stable and what can change

| Level | Preserve | Adaptation boundary |
|---|---|---|
| Invariants | Honest evidence, readable essential content, a clear entry point, meaningful relationships, coherent semantic roles | Never trade these for decorative resemblance |
| Heuristics | Suggested type ranges, margins, two or three supporting groups, short analytical headlines | Adjust for language, delivery mode, fair comparisons, assets, and actual rendering |
| Example choices | Specific position, aspect ratio, media choice, teaching words and numbers | Recompose whenever the new brief warrants it; they are not reusable facts or coordinates |

An override needs a reason tied to the communication task. A dense read-ahead may need more groups; a truthful comparison may need a wider table; an important product detail may need a closer crop. Explain the choice and check the resulting readability rather than claiming an exception from personal taste.

## Use the examples correctly

For each worked case, explain why its relationship fits the claim. Then change one constraint: a longer headline, no photography, a narrower canvas, a different audience, or evidence that contradicts the takeaway. Adapt the composition while preserving hierarchy and honesty. If the only possible answer is copying the example, the Style has not transferred.

## A useful handoff

When a deck is actually requested, deliver the editable artifact and a concise report of sources, assumptions, material open questions, and visual verification. Keep the full reasoning record available if requested. Do not clutter the product with implementation notes or a self-evaluation score.
