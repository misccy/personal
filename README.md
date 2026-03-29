# Academic Website for GitHub Pages

This package contains a lightweight bilingual academic personal website designed for GitHub Pages.

## Files
- `index.html` — Traditional Chinese homepage
- `index-en.html` — English homepage
- `styles.css` — site styling
- `robots.txt` — crawler instructions
- `sitemap.xml` — sitemap for search engines
- `assets/` — image, favicon, and CV placeholders

## What to replace before publishing
Search globally for these placeholders and replace them:
- `YOUR-DOMAIN`
- `YOUR_EMAIL`
- `YOUR_ID`
- `YOUR-ORCID`
- `YOUR_GITHUB`
- `YOUR_LINKEDIN`

## Recommended assets
Put these files in `/assets/`:
- `profile.jpg` or keep `profile.svg`
- `og-home.jpg` (recommended size: 1200 x 630)
- `CV-Chiang-Yu-Cheng.pdf`

## Deploy to GitHub Pages
1. Create a new GitHub repository, for example `academic-website`.
2. Upload all files in this folder to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save and wait for deployment.
7. Your site will be published at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## If using a custom domain
1. Add a `CNAME` file containing your domain, e.g. `www.yourdomain.com`.
2. Update the `canonical`, Open Graph URL, JSON-LD URL, and sitemap URL.
3. Point your DNS records to GitHub Pages.

## Suggested next steps
- Replace the placeholder publication entries with full APA references.
- Add your real photo and CV.
- Add project pages and a publications page later if needed.
- Add Google Search Console and Bing Webmaster Tools.
