# Portfolio

Static site: `index.html`, `styles.css`, `script.js`. No build step.

## Deploy with GitHub Pages

1. Create a new repository on GitHub, for example `Sebkh123.github.io` (using your exact
   username makes it your root site at `https://sebkh123.github.io`, no extra path).
2. Push these three files to the repository:
   ```
   git init
   git add index.html styles.css script.js
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/Sebkh123/Sebkh123.github.io.git
   git push -u origin main
   ```
3. On GitHub, go to the repo's **Settings → Pages**.
4. Under **Source**, select the `main` branch and `/ (root)` folder, then save.
5. GitHub will publish the site within a minute or two at the URL shown on that page.

If you'd rather keep it under a project repo instead of the special `username.github.io`
name, the same steps work, your site just lives at
`https://sebkh123.github.io/<repo-name>/` instead.

## Editing

- Copy and role details live directly in `index.html`, inside the `experience`, `stack`,
  and `education` sections.
- Colors and type live at the top of `styles.css` under `:root`.
