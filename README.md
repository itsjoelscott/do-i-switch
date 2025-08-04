# Should I Switch?

Single-page static comparison site showing differences between iPhone and Android features, with filters and search, and ad slot placeholders.

## Features

- Centered title and subheader.
- Filter by category dropdown.
- Search box to filter by keyword in feature or explanation.
- Sidebar ad slots ready for embedding ad network code.
- Basic analytics:
  - **Google Analytics (GA4)** integration placeholder. Replace `G-XXXXXXXXXX` in `index.html` with your actual measurement ID.
  - **Local browser pageview counter** (stored in `localStorage`) shown in footer as fallback.
- Mobile-responsive layout.

## Deploying on GitHub Pages

1. **Create a new GitHub repository** (e.g., `should-i-switch`) and push this project:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/should-i-switch.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to the repository on GitHub.
   - Settings > Pages.
   - Under "Source", select branch `main` and folder `/ (root)`.
   - Save. The site will be published at `https://<your-username>.github.io/should-i-switch/` (may take a minute).

3. **Customize analytics**:
   - Replace `G-XXXXXXXXXX` in `index.html` with your GA4 measurement ID.
   - Optionally swap in another analytics provider by replacing or augmenting the script.

4. **Add real ads**:
   - Apply for AdSense or sign up for Ezoic.
   - Once approved, replace the ad slot placeholders (`Ad Slot 1` / `Ad Slot 2`) with the provided ad code snippets.

5. **Optional enhancements**:
   - Add a `CNAME` file if using a custom domain.
   - Add `robots.txt` / meta tags for SEO.
   - Add a `LICENSE`, e.g., MIT.

## Example commit for enabling GitHub Pages
```bash
echo "yourcustomdomain.com" > CNAME  # if using custom domain
git add CNAME
git commit -m "Add custom domain"
git push
```

## Troubleshooting

- If the site doesn’t show after enabling Pages, wait a couple minutes and clear the browser cache.
- Ensure your repository’s default branch is `main` (or update GitHub Pages settings accordingly).

