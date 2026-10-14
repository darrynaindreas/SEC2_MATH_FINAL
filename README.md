# SEC2 Math Studio — GitHub Pages MVP

Static, single-student Math Studio using authoritative Math Learning Content Bank v12.1.

## Included
- 275 questions, 31 study notes, 275 explicit mappings and the original quadratic poster.
- Navigation: Practice → Study Notes → My Progress, with Practice first.
- Practice search/unit/progress filters, working drafts, solution reveal, self-marking, retries, timer.
- Study-note navigation from practice and return to the same question with draft, current position, reveal state and timer preserved.
- IndexedDB local progress, JSON backup/restore, progress reset.
- Original Redwood-inspired stylesheet and original 6px decorative stripe.

## Deploy on GitHub Pages
1. Create a GitHub repository and upload all files/folders **inside this folder** to the repository root (index.html, app.js, app.css, redwood-theme.css, assets/, data/). Do not upload the containing folder as an extra directory.
2. In repository Settings → Pages, choose Deploy from branch, `main`, `/ (root)` and save.
3. Open the Pages URL once the deployment completes. All URLs in this app are relative, so a project or username repository path should work.
4. To test locally use `python3 -m http.server 8000` inside the folder; visit http://localhost:8000/.

## Limitations / release notes
- Manual self-marking only, **not** automatic grading.
- Math expressions are source-preserved plain text; advanced mathematical typesetting and interactive diagrams are not implemented in this MVP.
- The visual study poster is preserved verbatim and can be enlarged. It and the 31 AI-written study notes have pending teacher review.
- Source data includes some review flags; they are not automatically suppressed in this MVP. Check pedagogical material before student publication.
- Browser IndexedDB is specific to this device/browser. Clear-site-data or private mode can remove progress. Export JSON backups regularly.
- No photo persistence, no cloud sync, no user login, no backend, no PWA/offline promise.
- The app should be exercised on your deployed GitHub Pages URL before treating deployment as verified.
