# Portfolio site notes

Public site that houses all my sports analytics projects. Kept separate from my private dashboard (`~/Desktop/my_dashboard`). Nothing from the dashboard goes here.
Say "add a note: …" in any chat in this folder and Claude adds it here. This file gets uploaded to GitHub, so no passwords or keys.

## How it's built
- One file: `index.html` (no frameworks, no build step). Hosted free on GitHub Pages.
- Design v3 "tech look": IBM Plex Sans + Mono, amber accent `#F4B544`, blueprint grid, SQL terminal in the hero.
- NFL case study shown as **In progress** with a build log until the real results are in.

## Before going live (search index.html for "EDIT")
- [x] Name: title, link-preview tags, nav `your-name_`, hero, footer
- [x] City in the status pill
- [x] Initials "WD" (swap in `images/photo.jpg` for a headshot)
- [x] Experience: real titles, companies, dates, results with numbers
- [x] About: replace the [brackets]
- [x] Skills: only what I can talk about in interviews
- [x] Email and GitHub (`wdouble2`) filled in
- [x] LinkedIn URL
- [x] `resume.pdf` (copy of WILLIAM DOUBLE RESUME.pdf, includes phone number)
- [ ] `images/preview.png` (1200x630)
- [ ] Add real numbers to experience bullets if I have them (% saved, hours, # of dashboards)
- [ ] GoatCounter: sign up, put my code in, uncomment the script at the bottom
- Rule: no placeholders, brackets or 00's go live.

## When the NFL project is done
- [ ] Terminal: replace the `…` row with the real numbers; change status line
- [ ] Tiles: swap the scope numbers for the 3 headline results
- [ ] Add Chart 1 (`images/nfl-home-win-by-season.png`) and a Findings paragraph
- [ ] Tag "In progress" → "Complete"; button → "View code on GitHub"
- [ ] Then post on LinkedIn

## Publish on GitHub Pages
1. Create a **public** repo named exactly `wdouble2.github.io`. Don't upload the two original resume PDFs, only `resume.pdf`.
2. Push `index.html`, `resume.pdf`, `images/`.
3. Settings → Pages → deploy from `main`.
4. Live at `https://wdouble2.github.io` in a few minutes.

## Ideas for later
- A page per project once there are 3+.
- Embed a Tableau Public / Power BI dashboard in a case study.
- Custom domain.
- Show GoatCounter visits on my private dashboard (reads the API; site unchanged).
