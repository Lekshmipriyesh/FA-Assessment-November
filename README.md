# Math Detective Agency: Teacher Console

Pick subject, date, class, section and session. The questions load automatically. Mark each student with a tick or cross, see the class analysis, and save the result to history.

## Put it on GitHub Pages
1. Create a new repository on GitHub (Pages is free for public repositories).
2. Upload `index.html`, `questions.js` and `README.md`.
3. Go to Settings > Pages. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. After a minute your link appears there. Share it with teachers.

## Good to know
- Saved results stay in each teacher's own browser. `roster.js` holds student names, so keep the repository private or remove that file before making it public.
- Use Export CSV in History to keep a backup or to combine results.
- Class lists for 6A to 8B are in `roster.js` (loaded from the SA-1 workbook). Names edited under Edit names override it on that device.

## Add more questions
Open `questions.js`, copy a chapter block and change it. Each row is `[session, type, question, answer]`. Type `D` is a direct application question and `I` is an indirect one. Refresh the page and the new session appears in the dropdown.
