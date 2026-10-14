# Raihan Rafeeq — AI/ML Portfolio (Sprint 5)

A lightweight static website: HTML + CSS + vanilla JavaScript. No backend, external libraries, package manager, or build step required.

## Test locally

Open `index.html` in your browser. Alternatively, in this directory run `python -m http.server 8000` and visit `http://localhost:8000`.

Use Chrome DevTools (`F12` then `Ctrl+Shift+M`) to test desktop, tablet, and phone layouts. Test the search and category filters, project card click and keyboard Enter, modal Escape/close behavior, demo controls, and CV download.

## Publish on GitHub Pages

1. Create a new public GitHub repository, ideally `RaihanRafeeq.github.io` if you want your website at `https://raihanrafeeq.github.io/`, or use another repository name for a project URL.
2. Upload `index.html`, `favicon.svg`, and `CV_AI_UAE.pdf` to the repository root. Keep all three together.
3. Open repository **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then Save.
4. Wait for GitHub Pages to publish; open the URL shown in Settings → Pages.
5. After you know the final URL, add an absolute `<link rel="canonical" href="https://YOUR-FINAL-URL/">` in `<head>` and set `og:url` to the same URL. Don't add a guessed canonical URL before choosing the repository.
6. Check the Email, LinkedIn, GitHub, CV, and project links on the published site.

## Final pre-publish checks

- Confirm CV contact and employment details are what you want publicly accessible.
- Verify external repository destinations (project names/links can change).
- The playground is illustrative, not live ML inference; retain those disclosures.
- Run Chrome DevTools Lighthouse for accessibility, SEO and performance on the published URL.
- Update the locally bundled CV whenever you revise your resume.

## Notes

The site's interactive demos use no external data. The design supports `prefers-reduced-motion`, keyboard focus indicators, a skip link, and responsive breakpoints. No analytics or tracking are embedded.
