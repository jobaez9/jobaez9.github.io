# jobaez9.github.io

My personal Data Analyst portfolio, built as a plain HTML/CSS/vanilla-JS static
site (no framework, no build step) and hosted for free via **GitHub Pages** at:

**https://jobaez9.github.io**

## Structure

```
index.html                     Homepage: hero section + project grid
projects/
  powerbi-project-1.html       Power BI project 1 (has a real shareable link)
  powerbi-project-2.html       Power BI project 2 (placeholder content)
  soccer-app.html               Soccer player/team/scout comparison app
assets/
  css/style.css                 All site styling
  js/main.js                    Mobile nav toggle (hamburger menu)
  images/                       Put your real screenshots here (see images/README.txt)
```

## How to personalize this site

1. **Replace placeholder text.** Search the project for `TODO` comments
   (`Ctrl+Shift+F` for "TODO" in your editor, or `grep -rn TODO .` in a
   terminal). Each one marks text you should personalize — project titles,
   descriptions, tech stacks, and links.

2. **Add real screenshots.** Drop image files into `assets/images/` using the
   suggested names in `assets/images/README.txt`. Then, in the matching HTML
   page, replace the `<div class="placeholder-box ...">...</div>` element with
   an `<img>` tag, for example:

   ```html
   <img src="../assets/images/powerbi-project-1-full.png" alt="Power BI Project 1 dashboard screenshot">
   ```

3. **Add a 4th project** (or more) later:
   - Copy one of the files in `projects/` as a starting point for the new page.
   - Add a matching `<article class="project-card">...</article>` block to the
     project grid in `index.html`, linking to your new page.

4. **Add a resume / contact / About Me section** whenever you're ready — it
   was intentionally left out for now to keep the initial site focused on the
   three projects.

## Deploying changes

This repo is a GitHub **user site** repo (`<username>.github.io`), so GitHub
Pages automatically serves whatever is on the `main` branch — there's no
separate build or deploy step. Just commit and push to `main`:

```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

Changes are usually live at https://jobaez9.github.io within a minute or two.
