# Shivani Kalal — Portfolio

Multi-page static site (no build step, no dependencies). Deploy as-is on GitHub Pages.

## Structure
```
index.html        Home — hero, animated pipeline diagram, stats, featured projects
experience.html    Work history timeline
projects.html      Full project write-ups (MARS, RagShield, LangFormer)
skills.html        Skills grouped by category
contact.html       Contact cards + message form (opens your email client)
styles.css         Design system + all styling
script.js          Mobile nav, active-link highlighting, scroll reveal, contact form
assets/            Resume PDF lives here
```

## Deploy to GitHub Pages
1. Create a repo (e.g. `portfolio`) on `github.com/Shivani176`.
2. Push these files to the repo root.
3. In repo Settings → Pages, set source to the `main` branch, root folder.
4. Site will be live at `https://shivani176.github.io/portfolio/`.

## Before you publish — update these
- **Project GitHub links**: all three project cards currently link to `github.com/Shivani176` (your profile). Point each one to its actual repo once public, e.g. `github.com/Shivani176/mars`.
- **Resume file**: already copied into `assets/Shivani_Kalal_Resume.pdf`. Swap in a new version any time you update it — the filename can stay the same so the download link keeps working.
- **LinkedIn URL**: uses `linkedin.com/in/shivani-rk` per your resume — double check the trailing slash/casing matches your real profile.

## Notes
- No frameworks, no npm install — open `index.html` directly in a browser to preview locally.
- The contact form has no backend; submitting it opens the visitor's email client with a pre-filled message (via `mailto:`). If you want it to actually submit without opening email, look at Formspree or a similar free form-backend service.
- Colors, fonts, and spacing are all defined as CSS variables at the top of `styles.css` if you want to adjust the palette later.
