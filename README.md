# Portfolio_Website
My Portfolio as a Data Analyst — Ishmal Khan.

Preview locally:

```bash
# serve the folder with a simple HTTP server (Python 3)
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

To deploy to GitHub Pages automatically:

1. Ensure this repository is pushed to a GitHub repo.
2. The workflow `.github/workflows/gh-pages.yml` will deploy `main` to the `gh-pages` branch on every push.
3. In the repository Settings → Pages, set the source to the `gh-pages` branch (if needed). The site will be available at `https://<your-username>.github.io/<repo-name>/`.

If you'd like, I can push the final commits and enable deployment to the existing remote `origin` — tell me to proceed and confirm you want to use the current `origin` remote (`https://github.com/<your-username>/<repo-name>.git`) or provide a different repo URL.
## Recent improvements
- Optimized large images (created `.opt.jpg` and `.webp` variants for background and profile images) to speed up page load.
- Added basic SEO meta tags, Open Graph tags, `robots.txt` and `sitemap.xml`.
- Improved accessibility: skip-link, aria-labels on social links and contact button, better image responsiveness.

Next steps I can do when you confirm:
1. Commit and push these changes to your repo and let the GitHub Pages workflow deploy the site.
2. (Optional) Configure a custom domain or deploy to Netlify/Vercel if you prefer.
3. Minify and bundle assets (CSS/JS) and add CI checks.

Tell me whether to use the current `origin` remote and whether you have a custom domain to set; I'll commit and push the changes once you confirm.