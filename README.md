# Sudanese Arabic A2: 100 interactive exercises

## Important: why the iPhone file preview did not save progress

The Files / Quick Look / ChatGPT preview of a downloaded `.html` file can block JavaScript or give each preview temporary storage. No HTML-only change can force iOS to keep that storage after closing. Multiple-choice checking in the standalone HTML now works with CSS even if JavaScript is blocked (requires a modern viewer), but saving answers still requires a proper website/web app context.

## Reliable iPhone version (PWA)

1. Upload ALL files from this folder (not the zip itself) to an HTTPS static web host such as GitHub Pages or Netlify. The host must serve `index.html` and the other files from the same folder.
2. Open the resulting HTTPS URL **in Safari** on your iPhone.
3. Tap **Share → Add to Home Screen**.
4. Launch from the newly added Home Screen icon. Complete question 1, close the app, then reopen to confirm your selection and score remain.
5. Save periodic progress backups with **Save progress file (.json)**. If downloads fail, open **Alternative: backup using copy and paste** and save the backup in Notes. This protects against website-data clearing, uninstalling, or changing devices.

When the HTML is opened as a local file or a Files preview, there is no guaranteed persistent storage. The website origin (https://...) is essential for the installable version; hosting is not included and must be set up separately. Progress stays on the device, not synced between devices.

## Testing

Question 1: choosing **B: Where have you been?** should immediately display a green “Correct!” message without clicking a grading button. Other options should show an incorrect message. Question 2: type a sentence and compare to the model; an arbitrary natural translation cannot be reliably auto-marked offline.

## File naming and compatibility

The app keeps the old storage key `sudanese-a2-exercises-static-v3`, and understands previous JSON progress backups. Storage from a local file is NOT transferred to a hosted URL automatically; import a JSON backup if you need to migrate.

## Hosting example: GitHub Pages

Create a GitHub repository, upload the files at its root, then Settings → Pages → Deploy from a branch → `main` / `(root)`. Once deployed, the URL will resemble `https://YOUR-NAME.github.io/YOUR-REPO/`. If the repository is public, the exercise content will be publicly viewable; your individual answers are saved locally in your browser, unless you export or share them.
