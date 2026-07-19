# Md Anas Kabir — Oracle DBA Portfolio

A single-page portfolio site (`index.html`) built for GitHub Pages. No build tools required — plain HTML/CSS/JS.

## What's included

- `index.html` — the site (content pulled from your CV: profile, certifications, skills, all 5 roles, 5 key projects, education, languages, contact info)
- `headshot.jpg` — your headshot, extracted from the CV PDF, used in the hero section
- This README

## 1. Two things to double-check

- **LinkedIn URL** — pulled directly from the hyperlink in your PDF: `linkedin.com/in/anas-kabir-mscse-ocp/`. Confirm it's still correct.
- **CV download button** — currently points to `./Md_Anas_Kabir_DBA.pdf`. Add your CV PDF to the repo root with that exact filename, or change the link/remove the button.

Everything else (experience bullets, projects, certifications, skills, education, contact details) was taken directly from your uploaded CV.

## 2. Publish with GitHub Pages

1. Create a new GitHub repository, e.g. `anas-portfolio` (or `<your-username>.github.io` if you want it at the root of your GitHub domain).
2. Push these files to the repo:
   ```bash
   git init
   git add index.html headshot.jpg README.md
   # also add your CV PDF here if using the download button
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then **Save**.
6. Your site will be live at:
   - `https://<your-username>.github.io/<repo-name>/` (normal repo), or
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`)

It can take 1–2 minutes to go live after the first deploy.

## 3. Optional next steps

- Add a favicon (`favicon.ico` in the root, linked in `<head>`).
- Add a custom domain via **Settings → Pages → Custom domain**, if you have one.
- Keep this in sync with your CV — when you tailor a CV for a specific application, update the portfolio's project/experience bullets to match if the numbers change.
