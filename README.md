# Sudanese Arabic A2 — Mixed grammar & exercise update (v6)

## Upload to GitHub Pages

**If you already have the app published:**

1. Download and unzip this package.
2. Open the same GitHub repository that hosts your Sudanese A2 app.
3. Replace **`index.html`** and **`sw.js`** at the **repository root** (commit both to the branch GitHub Pages deploys, usually `main`).
4. `manifest.webmanifest`, `icon-192.png` and `icon-512.png` can also be replaced, or kept if already installed. Upload all five if this is a new installation.
5. Visit the live GitHub Pages HTTPS URL in Safari while online, refresh, then launch your Home Screen app again. Sometimes it helps to close and reopen the Home Screen web app after the service worker updates.

**To avoid losing progress:** Export your saved `.json` progress first. The local-storage key `sudanese-a2-exercises-static-v3` and old question IDs `q-001`–`q-100` are unchanged, so saved progress should load on the **same site and same browser profile**. New exercises are `q-101`–`q-200`. If you change the GitHub Pages URL, previous local storage will not follow automatically; use JSON export/import.

## What's new

- 200 exercises in 10 integrated grammar-and-context units (original 100 retained, 100 new).
- English → Sudanese multiple choice, Sudanese → English multiple choice, typed **fill in the blank**, typed **verb conjugation**, free written Sudanese → English translation, and syntax rewrites.
- Type filter, immediate answer feedback for multiple choice and targeted short-answer exercises; spelling/diacritics normalization and accepted answer variants.
- Model answers, explanations, manually assessed free translations, offline-ready web app, browser progress save and JSON backup/import.
- Carefully separated right-to-left Arabic and left-to-right English text, including inputs and solutions.

**Important limitation:** Free open-ended translations are not AI-graded. Short-answer auto-checking uses a finite set of expected forms, so a legitimate alternative spelling can be marked "review"; compare the model answer. No API key is included.

Do not expect file previews on iOS to preserve progress. Use the published HTTPS app, ideally added to the iPhone Home Screen. Periodically export a JSON backup.
