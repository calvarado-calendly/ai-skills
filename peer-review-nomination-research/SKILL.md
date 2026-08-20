---
name: peer-review-nomination-research
description: Identify substantive peer review or 360-feedback nominees for a specified person and time period using authorized cross-source collaboration evidence while avoiding direct-report nominees when possible.
---

# Peer Review Nomination Research

Use this skill when the user wants peer review, 360-feedback, calibration, or performance-review nominee recommendations based on actual collaboration evidence.

The goal is not to find the most visible people. The goal is to identify people who likely had enough meaningful interaction with the review subject during the requested period to provide substantive, intentional feedback.

## Required Inputs

Before research starts, make sure these inputs are known. If any are missing, ask one concise question at a time.

- Review subject: the person being reviewed.
- Review period: exact start and end dates.
- Desired nominee count: target number of recommendations and whether alternates are useful.
- Direct-report context: known direct reports, likely indirect reports, or an authoritative org-chart source to check.

If the user gives relative dates, restate the absolute dates you will use.

## Source Coverage

Use every authorized source that can materially show collaboration. Typical sources include Slack, Jira, Confluence, GitHub, Google Drive, Google Calendar, Gmail, meeting notes, and docs or sheets referenced by those systems.

Cover private sources only when the user has requested or authorized them for this nomination task. Slack research should include relevant DMs, private channels, public channels, group DMs, and threads when available.

For each source, distinguish:

- `searched`: used directly in the current run.
- `not available`: no connector, access, or permission.
- `not searched`: intentionally skipped, with the reason.
- `incomplete`: searched but pagination, access limits, result caps, or time constraints prevented full coverage.

Do not describe the research as comprehensive unless bounded pagination and relevant result sets were actually exhausted.

## Research Approach

Start broad enough to discover candidate collaborators, then narrow quickly.

- Resolve the review subject's likely names, handles, email address, and IDs in each system before relying on searches.
- Use date-bounded searches for the exact review period.
- Search both directions where useful, such as messages from the subject, messages to or mentioning the subject, comments authored by the subject, and artifacts edited or reviewed by the subject.
- Prefer interaction evidence over proximity evidence. A recurring meeting without substantive notes is weaker than a thread, review, doc, issue, or decision record showing actual collaboration.
- Read targeted threads, comments, documents, meeting notes, pull requests, and issue discussions for promising candidates. Do not rank people from search snippets alone when fuller context is accessible.
- Filter out bots, calendar notifications, automated GitHub/Jira messages, and pure broadcast traffic.

Look for evidence that a candidate can comment on one or more review-relevant dimensions:

- Execution quality, judgment, reliability, and follow-through.
- Technical or product decision-making.
- Cross-functional collaboration and stakeholder management.
- Communication style, influence, or conflict handling.
- Leadership, delegation, coaching, or operating model.
- Incident, launch, planning, roadmap, or delivery behavior.

## Direct-Report Avoidance

Avoid recommending direct reports of the review subject when a reasonable alternative exists. Also flag likely indirect reports or reporting-line ambiguity.

Use authoritative sources when available, such as HRIS exports, org charts, manager rosters, calibration spreadsheets, or clearly maintained team docs. If only contextual clues are available, label the relationship as inferred and assign a confidence level.

Do not exclude a candidate solely because they are on the same team. Exclude or downgrade when they are a direct report, likely indirect report, or when the feedback dynamic would be materially compromised.

## Candidate Evaluation

Rank candidates by likely feedback quality, not seniority or volume alone.

Strong candidates usually have:

- Multiple substantive interactions during the period.
- Evidence across more than one channel, artifact, project, or meeting type.
- A distinct perspective that is not duplicated by stronger candidates.
- Enough context to discuss behavior and impact, not just outcomes.
- No direct-report conflict, or a clearly disclosed relationship caveat.

Weak candidates usually have:

- Only passive meeting attendance.
- Mostly automated or administrative contact.
- One narrow interaction with little behavioral signal.
- A likely reporting-line conflict.
- Evidence that is stale or outside the review period.

Use confidence labels such as `high`, `medium`, and `low`, and explain the reason. Treat confidence as a judgment about feedback usefulness and evidence quality, not a claim about the person.

## Output

For a full nomination packet, read [references/nomination-packet.md](references/nomination-packet.md) and follow that structure unless the user requests a different format.

Keep the final answer evidence-led and decision-ready. Include direct source links when tools provide stable links. Anonymize private-source themes only if the user asks for a shareable artifact that should not expose private messages or sensitive comments.
