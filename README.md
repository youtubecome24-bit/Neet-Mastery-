# NEET Master Pro

A responsive, installable NEET study tracker and practice app.

## Included
- Dashboard with subject activity, XP and levels
- MCQ practice, sample questions, and your own MCQ bank
- Active-recall flashcards
- Mock-test result recorder and history
- Revision planner with completion tracking
- Performance analysis and weak-topic summary
- Offline local study assistant named **Demon king- Kali** (rule-based helper; not a connected cloud AI model)
- Custom NEET Master app icon in PNG sizes 192×192 and 512×512
- Local data storage, JSON backup export/import
- PWA manifest and service worker for install/offline caching

## Publish on GitHub Pages
1. Extract this ZIP.
2. Open your GitHub repository (for example `Neet-Master`).
3. Upload **all files inside this folder** to the repository root (not the ZIP itself).
4. Commit the changes to the `main` branch.
5. In Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
6. Wait for the green `github-pages` deployment. Open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
   - For a user site repository named `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`.

## About the AI
The included **Demon king- Kali** assistant is an offline, rule-based study helper. A real ChatGPT-style model needs a server-side API integration. Do **not** place a private API key in `index.html` or any public GitHub repository. Add a backend endpoint and keep the key in a server environment variable before enabling a cloud model.

## Data and limitations
- Progress is saved in browser localStorage on this device/browser only. It does not automatically sync between devices.
- Use Export backup regularly; Restore backup imports a JSON backup.
- The sample questions are basic illustrative examples, not a complete NEET question bank. Add verified questions from your own study material.
- Mock tests are recorded by you; this version does not include a full official NEET paper or a live timed test engine.
- Not affiliated with NTA.
\n\nProgress overview update: dashboard includes overall targets for 120,000 questions, 600 tests and 2,000 study hours. Subject allocations: 40,000 questions and 200 tests per subject; study-hour allocation Physics 800, Chemistry 650, Biology 550. Built-in MCQ attempts count automatically; use dashboard forms for external question totals and study hours.\n