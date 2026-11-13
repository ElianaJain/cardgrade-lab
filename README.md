# Cardgrade Lab

A personal project exploring AI-assisted trading card grading with a human in the loop. Computer vision measures what can be measured, a vision-language model explains findings, and a person makes every final call.

**Live demo:** https://[your-username].github.io/cardgrade-lab/

## What works today

- **Centering tool** (`index.html`): upload a card photo, drag four lines onto the inner border, and get left/right and top/bottom ratios with an adjustable "send to reviewer" threshold. Runs entirely in the browser; images are never uploaded.

## Roadmap

- [ ] Automatic card and border edge detection
- [ ] Corner, edge, and surface scoring (needs a labeled image set)
- [ ] Confidence-based review queue with human sign-off
- [ ] Validation against cards with known grades
- [ ] Counterfeit and alteration flags

## Deploy to GitHub Pages

1. Create a new public repo named `cardgrade-lab` on GitHub.
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: centering tool and project page"
   git branch -M main
   git remote add origin https://github.com/[your-username]/cardgrade-lab.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at the URL above.
5. Replace the `[Your name]` and `[your-username]` placeholders in `index.html` and this file.

## Disclaimer

Independent personal project. Not affiliated with or endorsed by any grading company, and it does not produce official grades.
