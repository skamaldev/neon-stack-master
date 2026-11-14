# Neon Stack Master — updated website package

Static HTML5 Canvas game and supporting pages. No build step or API key is required.

## Files
- `index.html` — game, accessible page content, SEO metadata
- `about.html` — gameplay instructions
- `privacy.html` — current project privacy disclosure
- `terms.html` — terms of use
- `robots.txt` and `sitemap.xml` — crawler files for the published GitHub Pages URL
- `manifest.webmanifest` — basic install metadata

## Publish to the existing GitHub Pages repository
1. Back up/download the current repository first.
2. Upload/replace these files in the repository root (keep the existing repository name `neon-stack-master`).
3. Commit the changes to the branch/folder configured in GitHub Pages.
4. Wait for deployment, then check the homepage, `/about.html`, `/privacy.html`, `/terms.html`, `/robots.txt`, and `/sitemap.xml`.

Canonical site URL: https://skamaldev.github.io/neon-stack-master/

## Search Console
1. Add the URL-prefix property `https://skamaldev.github.io/neon-stack-master/`.
2. Verify ownership using the HTML tag Google provides; add that exact meta tag inside `<head>` in `index.html`, commit, then click Verify.
3. Submit `sitemap.xml` and inspect the homepage with URL Inspection. Indexing is not guaranteed.

## Adsterra integration — not yet enabled
This package intentionally contains **no Adsterra publisher script**. Do not paste random scripts from tutorials. First add the site in your own Adsterra publisher account, wait for approval, choose a suitable ad format, and copy the exact code from your dashboard. Share that code if you want help placing it safely. Start with one clearly-labelled, non-intrusive placement outside the game controls. Do not represent a normal banner as a rewarded ad. The in-game Continue button is a free continuation, not an ad reward.

Before enabling ads, update the privacy disclosure and implement any consent mechanism required for the actual ad provider and target regions. Check the provider's current publisher terms and GitHub Pages acceptable-use rules.

## Social preview image
A social preview image has not been included. Create and add a real 1200×630 PNG and then add matching `og:image` and `twitter:image` metadata before relying on rich social previews.

## Important notes
- Game progress is stored in browser localStorage and is device/browser-specific.
- The game uses Pointer Events for canvas input to avoid handling the same touch twice through both pointer and touch listeners.
- The game animation loop runs only while a game round is active.
- Test on real mobile and desktop browsers after deployment.
