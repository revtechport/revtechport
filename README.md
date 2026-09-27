# RevTechPort

Source for [revtechport.com](https://revtechport.com), hosted free on GitHub Pages.

## Structure

- `index.html` — homepage
- `blog/index.html` — blog listing page
- `blog/<slug>.html` — individual posts (add new ones here)
- `assets/` — images (headshot, logos)
- `CNAME` — tells GitHub Pages to serve this at revtechport.com instead of the default github.io address

## Publishing a new blog post

1. Create `blog/<slug>.html` following the same visual style as the homepage (navy/brass palette, Fraunces + Inter fonts — see `index.html` for the shared CSS).
2. Add an entry to the `<!-- POSTS_START --> ... <!-- POSTS_END -->` block in `blog/index.html`, newest first.
3. Commit and push. GitHub Pages rebuilds automatically within a minute or two.

## Hosting

No build step, no server, no monthly cost — this is served directly from the repo by GitHub Pages. Enabled under the repo's Settings → Pages, with the custom domain set to revtechport.com (matching the `CNAME` file) and DNS pointed at GitHub's servers via records at the domain registrar (Namecheap).
