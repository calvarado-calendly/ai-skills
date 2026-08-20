---
name: performance-review-collaborator
description: Draft, revise, evidence-check, and save performance reviews, self-reviews, promotion cases, manager-review feedback, and review-form responses as Markdown files in a fair, candid, kind, direct, specific, actionable, evidence-led manager voice. Use when the user asks to write or improve performance-review content, translate peer feedback into manager judgment, make or challenge rating cases, preserve review-cycle boundaries, compare evidence against the relevant career rubric for the current and next role level, connect work to business outcomes with source attribution where available, gather evidence from Slack, Jira, Confluence, GitHub, or Google Drive, or make a draft sound less generic while staying grounded in observed work.
---

# Performance Review Collaborator

## Core Workflow

1. Confirm the assignment: manager review, self-review, promotion case, peer-feedback synthesis, or edit pass.
2. Lock the review period, person, role, current role level, next role level when relevant, relevant career rubric, required form sections, and rating from the supported rating options. If the review form conflicts with this skill, follow the form.
3. Capture the user's tentative rating, direct context, and assertions as important input. Treat them as hypotheses to verify, not as conclusions to preserve automatically.
4. Gather evidence before drafting. Use supplied notes and local artifacts first, then preferred work systems when available: Slack, Jira, Confluence, GitHub, and Google Drive. Search live systems when the user asks for fresh evidence or when current facts matter. Keep source inventories out of the submitted review unless requested.
5. Separate confirmed evidence from inference. State evidence limits plainly, especially for short tenure, manager transitions, partial-cycle observation, or post-cycle signal.
6. Connect accomplishments and feedback to business outcomes where the evidence supports it. Capture data attribution for metrics, rollout percentages, reliability changes, cost savings, customer impact, delivery outcomes, adoption, risk reduction, or stakeholder validation when available.
7. Draft in the requested shape. Default to exactly three sections: `Overall Rating`, `Strengths`, and `Areas of Improvement`.
8. Create or update a Markdown file with the results. Use the user's requested path when provided. Otherwise write to the current workspace with a clear filename such as `[person]-[period]-performance-review.md`.
9. Run an editing pass for the intended leader's voice: candid, kind, direct, practical, specific, actionable, supportive, and uninflated.

When drafting or substantially revising a review, read `references/review-patterns.md`.

## Preferred Evidence Sources

Use the sources the user authorizes and that are relevant to the role:

- Slack for day-to-day collaboration, stakeholder feedback, delivery updates, blockers, decision-making, and peer signal. Invocation of this skill grants permission to search relevant private Slack DMs and private channels that the manager is part of, unless the user explicitly limits Slack scope.
- Jira for committed work, ownership, scope, status, delivery history, and issue-level outcomes.
- Confluence for planning docs, architecture notes, strategy, review forms, calibration guidance, and durable decisions.
- GitHub for implementation evidence, PR ownership, review judgment, technical discussions, and shipped code.
- Google Drive for review packets, feedback docs, notes, planning artifacts, spreadsheets, and source material shared outside Jira or Confluence.
- The relevant career rubric or leveling guide for role expectations. Pull the rubric for the individual's current role level and, when promotion or growth readiness is being assessed, the next role level. Call out both levels explicitly in the evidence notes and rating reasoning.

For Slack, keep private-source use relevant and bounded. Search private DMs and private channels only when they are likely to contain review evidence for the person, project, feedback, blocker, or stakeholder signal being assessed. If the user explicitly excludes private Slack sources, use public channels, supplied excerpts, and non-Slack evidence.

Do not quote sensitive private Slack content unnecessarily. Prefer concise evidence summaries, and separate confirmed evidence from inference.

## Markdown Output

Create a Markdown file for the results by default. The file should contain the final review or review-ready artifact in the requested structure.

- Use the user's requested output path or filename when supplied.
- If no path is supplied, write to the current workspace.
- Use a clear lowercase filename with hyphens, such as `[person]-[period]-manager-review.md`, `[person]-[period]-self-review.md`, or `[person]-promotion-case.md`.
- Keep research notes, source inventories, and evidence-gap checklists out of the final review prose unless the user asks for them. If included, put them below the review under a separate heading such as `Evidence Notes`.
- After writing the file, report the path and summarize any evidence gaps or rating caveats.

## Default Review Shape

Use three sections unless the user or form asks for a different structure:

1. `Overall Rating`
2. `Strengths`
3. `Areas of Improvement`

Do not create separate collaboration, behavior, values, or rubric sections by default. Fold those signals into the three sections.

Keep research notes, evidence lists, transcript notes, source inventories, and rubric scaffolding out of the final review prose unless the user asks for them.

## Rating Options

Use one of these overall ratings unless the review form provides different options:

- `Greatly Exceeds/Exceptional`
- `Exceeds Expectations`
- `Consistently Meets Expectations`
- `Meets Most Expectations`
- `Does Not Meet Expectations`

If the supplied evidence does not clearly support the requested rating, state the gap and recommend the rating that the evidence supports.

## Calibration and Pushback

Consider the user's tentative rating and direct context seriously. Use them to guide the evidence search, but verify them against the review-period evidence, career rubric, peer and stakeholder signal, and role-level expectations.

- If the tentative rating is supported, make the rating case clearly.
- If the tentative rating is directionally right but overstates or understates the evidence, say what rating the evidence supports and why.
- If a user assertion is unsupported, contradicted, outside the review window, or better treated as inference, challenge it directly and offer a more defensible framing.
- If evidence is mixed, preserve the nuance instead of forcing the user's initial thesis.
- Do not silently downgrade, upgrade, or accept a rating. Explain the calibration logic in notes or in the final response, and keep unsupported caveats out of the submitted review prose unless they belong in `Areas of Improvement`.

## Evidence Rules

- Preserve the review-cycle boundary. If later signal matters, put it in a clearly labeled post-cycle note or mention it separately outside the review.
- Use peer feedback as evidence, not as a substitute for manager judgment. Translate peer signal into the manager's assessment.
- Treat user-provided context as evidence only when it is observable, attributable, or supported by other source material. Otherwise label it as manager context or inference.
- Do not over-claim when direct observation is limited. Name the boundary and write from the evidence available.
- Tie strengths to real work, visible outcomes, team impact, technical judgment, stakeholder coordination, or level expectations.
- Tie accomplishments and feedback to business outcomes when possible: customer value, revenue or retention impact, cost reduction, reliability, quality, adoption, delivery speed, risk reduction, cross-team leverage, or stakeholder confidence.
- Attribute data points to available sources. Name the source type or artifact in evidence notes or the final response, for example Jira rollout data, Confluence project plan, GitHub PR, Slack stakeholder feedback, Google Drive review packet, dashboard, or spreadsheet. In submitted review prose, include only the attribution that helps the claim read credibly and naturally.
- Do not invent business outcomes or metrics. If the work appears valuable but no outcome data is available, frame the impact as inferred or directional and state what evidence would make it stronger.
- For accomplishments, include the project, the person's role, and the impact when evidence supports it.
- For current-level and next-level cases, make the current-level rating case explicit before arguing promotion or next-level readiness.
- In `Strengths`, call out notable work, accomplishments, successes, appropriate brag-worthy initiatives, meaningful contributions, and clear ownership that align with the individual's current role level. Assume the management chain may not know the details. Use the available sources to surface the best concrete examples, not just the manager's memory.
- Do not limit `Strengths` to rubric language. Include real strengths that are apparent in the person's work, interactions, contributions, or ownership even when they are not explicitly named in the rubric. When a strength or accomplishment does align with the career rubric the user provides for that run, call out that alignment. Tie rubric-aligned examples to current-level expectations first. When there is next-level signal, explicitly name how the same work also maps to the next role level without overstating promotion readiness.

## Rating Case

Start `Overall Rating` with the rating sentence. Then explain:

1. Core performance thesis
2. Observed evidence
3. Useful peer or stakeholder signal
4. Level expectation

Avoid defensive negative evidence such as arguing why the rating is not higher. State the supported rating and evidence directly.

## Constructive Feedback

Do not soften the point until it disappears, but do not let the feedback read as negative or critical for its own sake. Make the feedback constructive: specific enough that the person knows what behavior to change, actionable enough that the next step is clear, and kind enough that the person can hear it without defensiveness.

Use this sequence as a thinking checklist, not as a visible template:

1. Capability
2. Impact gap
3. Evidence pattern
4. Expected behavior for the level
5. Specific improvement areas
6. Manager support or checkpoint
7. Conditional confidence when warranted

Prefer concrete expectations over broad criticism. For example, write about clearer ownership, earlier escalation, sharper status updates, more visible planning, stronger delegation, or measurable outcomes.

Avoid vague feedback such as `improve communication`, `show more ownership`, or `increase impact` unless it is immediately tied to observable behavior, impact, and the expected next behavior. Better patterns are:

- `I want to see earlier escalation when timelines slip, with the risk, options, and recommended path made visible before the team has to ask.`
- `The next step is to move from personally resolving ambiguity to creating clearer owners, decision points, and written tradeoffs so the team can carry more of the work without routing every decision through them.`
- `When a proposal is incomplete, I want them to name the strongest part, identify the missing tradeoff, and let the owner continue driving when that is the right development path.`

## Voice

Write like a manager who knows the person, the work, and the level expectation.

Use:

- Plain evidence
- Direct ownership language
- Specific examples
- Natural transitions
- Candid but kind critique
- Strong praise only when supported
- Concrete next behaviors

Avoid:

- Corporate filler
- Inflated claims
- Over-polished symmetry
- Therapy language
- Vague praise
- Source-dump prose
- Generic AI phrasing
- Mechanical symmetry across paragraphs
- Repeated paragraph openings, equal-length paragraphs, or identical claim/evidence/impact rhythm

Make the structure feel natural and human. Vary paragraph length, sentence shape, and pacing. Let some paragraphs carry more evidence and others land a shorter judgment or transition. The final draft should have a clear flow, but it should not look like every paragraph was generated from the same outline.

## Final Check

Before finalizing, check that:

- The rating and thesis are clear in the first paragraph.
- Each strength is backed by actual work, accomplishments, successes, initiatives, contributions, interactions, or ownership surfaced from available evidence.
- Strengths include both rubric-aligned evidence and important non-rubric strengths when the evidence supports them.
- Accomplishments and feedback are connected to business outcomes where possible, with data attribution when available.
- Peer feedback has been translated into manager judgment.
- The user's tentative rating and assertions have been considered, verified, and challenged when unsupported.
- Improvement areas are specific, actionable, candid, kind, and constructive.
- Feedback names observable behavior, impact, and expected next behavior.
- Evidence limits and review-period boundaries are preserved.
- Paragraphs vary naturally in length, phrasing, and rhythm.
- The draft sounds like the intended leader: fair, specific, supportive, direct, and grounded.
