# Neon Stack Master – Web Game Package

Complete static website ready for free hosting + Adsterra monetization.

## Files Included

| File | Purpose |
|------|---------|
| `index.html` | Main game + landing page (SEO ready) |
| `about.html` | How to Play page |
| `privacy.html` | Privacy Policy (required by Adsterra & Google) |
| `terms.html` | Terms of Service |
| `robots.txt` | Search engine crawl rules |
| `sitemap.xml` | Sitemap for Google Search Console |
| `manifest.webmanifest` | Add-to-Home-Screen / future PWA support |

## Free Hosting Options (Recommended)

1. **GitHub Pages** (best for long term)
   - Create a new public repository
   - Upload all files
   - Settings → Pages → Deploy from main branch
   - Your site will be at `https://username.github.io/repo-name/`

2. **Netlify** (very easy + free SSL)
   - Drag & drop the folder at netlify.com/drop
   - Or connect GitHub repo

3. **Cloudflare Pages**
4. **InfinityFree / other free web hosts** (good for Adsterra approval sometimes)

## Before Going Live

1. Replace every `YOUR-DOMAIN.com` with your real domain in:
   - `index.html` (Open Graph & Twitter meta tags)
   - `robots.txt`
   - `sitemap.xml`

2. Create a simple `og-image.png` (1200×630 recommended) showing the game title + neon blocks. Place it in the root folder.

3. Add Adsterra ads:
   - Banner or Native in non-intrusive places
   - Interstitial on "Play Again"
   - **Rewarded** on the Continue button (best revenue)

## Google Indexing Steps

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your property (domain or URL prefix)
3. Submit `sitemap.xml`
4. Request indexing for the homepage

## Free Traffic Ideas

- Share score feature (already built – uses native share)
- Post short clips on TikTok / Reels / Shorts (“Can you beat my score?”)
- Reddit: r/WebGames, r/incremental_games, r/somethingiswrongwiththisgame etc.
- Discord gaming servers
- Make a simple “Daily Challenge” post every day

## Future Play Store Path

Because the game is pure HTML5 + Canvas, you can later wrap it with:
- Capacitor
- Cordova
- or PWA Builder

and publish as a TWA / Android app when you have budget and traction.

## Notes

- All progress is saved in browser localStorage (no backend needed)
- Fully responsive and mobile-first
- No external dependencies – works offline after first load
