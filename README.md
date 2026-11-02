# Sudanese Arabic: CEFR audit and level reclassification (v9)

All **212** existing question IDs are preserved, with unchanged prompts, answers, explanations and answer choices. **194** remain A2; **18** are moved into **three B1 starter units**. A1 and B2 remain placeholders. B1 is a *starter set*, not a full B1 course.

## B1 units
- Relative clauses & embedded questions (10): q-002, q-006, q-068, q-076, q-088, q-105, q-110, q-120, q-161, q-208
- Linked events & contrast (4): q-074, q-124, q-142, q-152
- Hypothetical situations & extended expression (4): q-098, q-100, q-199, q-200

## Criteria
The assessment is based on the communicative task (not a fixed grammar checklist): familiar routine exchanges and short, directly linked statements stay A2, while productive embedded questions/relative clauses, interrupted narratives, concession and counterfactual or extended output move to B1. Borderline formulaic first conditionals and simple relative-clause comprehension stay at upper A2. CEFR is a flexible framework, not a Sudanese-specific calibrated test.

## Compatibility and storage
The existing localStorage key `sudanese-a2-srs-v7` and JSON backup format are preserved. Question IDs, grades, SRS records, user feedback, weak construction notes, and answer drafts remain intact. Unit percentages are **recalculated** against the new A2/B1 allocation. The A2 daily-review generator excludes B1 exercises until B1 is explicitly opened. The B1 starter units use the same local progress. Export a progress backup before installing.

## Update GitHub Pages
Upload/replace `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, and `icon-512.png` from this ZIP at the repo root, then commit. The new service-worker cache version makes the published update refresh after deployment. Open **Courses → A2** or **Courses → B1**. Exported CSV includes all 212 classifications and their reasons.

Limitation: this audit is pedagogical judgment; actual level requires human field validation. No questions or lesson content were rewritten.

The script-free fallback also groups all 212 questions under their A2 and B1 units.
