# Goutham Ravi Kumar Ravutla — PM Portfolio

Static multi-page site + a local admin form.

## Public site (goes in the GitHub repo)
- index.html   — About
- work.html    — Work: Blogs (topic-wise) + Projects (each with related articles). Reads content from data.json.
- contact.html — Email + LinkedIn
- data.json    — ALL blog/project content lives here (edited by the admin form)
- styles.css / script.js

## admin.html (KEEP LOCAL — do NOT upload to the repo)
A form to add blogs/projects. Open it in your browser, paste your GitHub token,
Connect, fill the form, Publish. It commits to data.json and the live site updates in ~1 min.

## Deploy the site
1. Copy index.html, work.html, contact.html, data.json, styles.css, script.js into your repo folder
2. git add -A && git commit -m "Data-driven site" && git push
3. Settings -> Pages -> main -> / (root)

## SEO / social
og-image.png, favicon.png, apple-touch-icon.png, sitemap.xml, robots.txt are in the repo root.
To regenerate the OG card later, re-run the image script or ask.

## Blog/article source
Each blog and project article has a "Source" (LinkedIn, Medium, Substack, etc.). The card badge
and colour follow the source automatically. Set it in the admin form.
