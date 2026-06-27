# Vignesh V — Portfolio Site

A single-page personal portfolio site, ready to deploy on GitHub Pages for free.

## Files
- `index.html` — the entire site (HTML, CSS, and JS in one file)
- `assets/Vignesh_V_Resume.pdf` — downloadable résumé, linked from the "Download Résumé" buttons

## Deploy on GitHub Pages (free, ~5 minutes)

1. **Create a new GitHub repo**
   - Go to https://github.com/new
   - Name it anything — a common convention is `<your-username>.github.io` (this gives you a clean root URL), but any name works too.
   - Keep it public (GitHub Pages on free accounts requires public repos).

2. **Upload these files**
   - On the repo page, click "Add file" → "Upload files"
   - Upload `index.html` and the `assets` folder (with the PDF inside it), keeping the same folder structure
   - Commit the changes

3. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Build and deployment," set **Source** to "Deploy from a branch"
   - Set **Branch** to `main` (or `master`) and folder to `/ (root)`
   - Click **Save**

4. **Wait ~1-2 minutes, then visit your site**
   - GitHub will show you the live URL at the top of the Pages settings (something like `https://yourusername.github.io/repo-name/`)
   - If you named the repo `yourusername.github.io`, your site will be at the cleaner `https://yourusername.github.io/`

## Updating content later
Just edit `index.html` directly (it's plain HTML/CSS/JS, no build step) and re-upload, or push changes via `git` if you're comfortable with the command line:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Pages auto-redeploys within a minute or two of any push to the configured branch.

## Adding a custom domain later
If you ever buy a domain, GitHub Pages supports it: add a `CNAME` file with your domain name, then configure your domain registrar's DNS to point at GitHub Pages (instructions: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).
