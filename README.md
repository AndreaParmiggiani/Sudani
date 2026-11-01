# Sudanese Arabic – course navigation (v8)

This update preserves the existing 212 A2 questions, 12 grammar paths, spaced repetition, weak-construction tracking, per-question feedback and JSON progress backups.

## Navigation
- **Courses:** A1, A2, B1, B2. A2 is available; other levels are placeholders.
- **A2 units:** 12 grammar-led units, each with unique assigned questions, showing number answered, completion percentage and complete/in-progress state.
- **Unit practice:** one question at a time with immediate grading or written self-rating, Previous and Next controls. Next becomes available after grading or self-rating that question.
- **Unit finish:** automatically saves completion after the final question and returns to a completion screen; use Back to A2 units to view the updated status.
- **Daily review/weak constructs:** continue as before, separate from course completion tracking.

## Progress saving and compatibility
- Auto-saves to existing browser localStorage key `sudanese-a2-srs-v7` after each answer, question navigation, and on unit completion.
- Preserves old progress and backup format `sudanese-a2-srs` v7. New `unitCursor` and `completedUnits` fields are included in backups.
- A unit is counted completed once all its uniquely assigned questions have been graded or self-rated at least once (even if some were wrong; weak items remain scheduled for review).
- Export a backup before updating. Same GitHub Pages origin + Home Screen app needed for existing browser-stored progress.

## GitHub Pages update
1. Extract this zip.
2. Upload `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` to your existing GitHub repository root (replace older versions).
3. Commit to main; refresh the GitHub Pages site and reopen the Home Screen app.
4. If old pages remain cached, close/reopen the app or reload once online.

## Limitations
- A1, B1 and B2 contain no exercises yet.
- Progress is stored on device, not synchronized through GitHub; periodically export JSON.
- Written translations are self-rated, not AI graded.
- Unit grouping is by primary grammar concept: a question may still have secondary concepts used by spaced repetition.
- Editing local HTML in iOS Files may not persist storage. Hosted HTTPS web app recommended.

Unit distribution: {"requests": 18, "conversation": 15, "objects": 19, "describing": 18, "present": 18, "negation": 19, "time": 21, "motion": 18, "comparison": 17, "conditionals": 19, "relatives": 10, "clauses": 20}
