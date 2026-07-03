# Goutham — PM Portfolio

Static site (HTML/CSS/JS). No build step. Hosts free on GitHub Pages.

## Files
- `index.html` — main page (hero, about, skills, case studies, blog links, contact)
- `styles.css` — all styling
- `script.js` — nav + scroll reveal
- `blog/prioritization.html`, `blog/shipping-ai.html` — sample posts

## Fill in your details
Search-and-replace these placeholders across all files:
- `[EMAIL]` → your email
- `[LINKEDIN_URL]` → your LinkedIn profile URL
- `[RESUME_LINK]` → link to your résumé (e.g. a Google Drive/Dropbox share, or a `resume.pdf` you drop in this folder)

Then edit the real content: About paragraphs, the 3 case studies (numbers, what you owned), and skills tags.

## Add a new blog post
Copy any file in `blog/`, rename it, edit the content, then add a card for it in `index.html` under the `<div class="posts">` section.

## Deploy to GitHub Pages
1. Create a GitHub account, then a new **public** repo. Name it `yourusername.github.io` for a root URL, or any name for a `/repo` sub-path.
2. Upload all these files (keep the `blog/` folder). Web UI: repo → **Add file → Upload files** → drag everything in → **Commit**.
3. Repo → **Settings → Pages**. Under *Build and deployment*, Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
4. Wait ~1 minute. Your site is live at `https://yourusername.github.io/` (or `/repo-name/`).

Any future edit you commit auto-redeploys.

## Custom domain (optional)
Settings → Pages → Custom domain. Add your domain and point a CNAME/A record at GitHub per their prompt.
