# EastBio Agent Skill

A portable Agent Skill for answering questions about the University of Edinburgh EastBio Doctoral Landscape Award / Doctoral Training Partnership.

## Contents

- `SKILL.md` — routing, source-grounded answering rules, currency safeguards, and topic map.
- `references/EastBio_complete_site_capture.md` — the user's supplied 100-page automated capture, dated 2026-10-15.
- `tests/evaluation-cases.md` — acceptance cases for intended-runtime evaluation.

## Install/use

Copy the `eastbio` directory into the target agent runtime's skills directory, then invoke or let the agent route to the skill. The supplied reference should remain beside `SKILL.md` at `references/EastBio_complete_site_capture.md`.

## Source limitations

The capture is not a verified exhaustive crawl and is not live policy. It may omit orphaned, non-indexed, removed, dynamically rendered or media/document content. Verify current deadlines, eligibility, funding terms, project availability, vacancies, contacts and events against the official live pages and UKRI terms before presenting them as current.

## Validation status

Package structure and core metadata are checked by the creator. Evaluation cases are included but have not been run by an isolated agent runtime; they must be exercised before production deployment.
