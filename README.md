# GUR landing page

Placeholder one-pager for LemonSqueezy merchant verification. Three files,
static, no build step.

## Fastest deploy — Netlify Drop (~30 seconds, free, no account needed)

1. Open <https://app.netlify.com/drop>.
2. Drag this entire `landing/` folder onto the drop zone in the browser.
3. Netlify gives you a URL like `https://wonderful-name-12345.netlify.app`.
4. Paste that URL into the LemonSqueezy "Website URL" field.

You can claim the site afterwards with a free Netlify account, rename the
subdomain, and connect a custom domain later — the URL stays the same until
you change it.

## Alternative deploys

- **GitHub Pages** — push `index.html` + assets to a public repo, enable
  Pages on the `main` branch root. URL: `https://<user>.github.io/<repo>/`.
- **Cloudflare Pages / Vercel** — same drag-and-drop or connect-the-repo flow.

## Files

| File           | Purpose                              |
|----------------|--------------------------------------|
| `index.html`   | Single-page site, inline CSS         |
| `gur_logo.png` | Brand wordmark (header)              |
| `favicon.ico`  | Browser tab icon                     |

## Editing

Open `index.html` and edit directly — there is no build step. Redeploy by
re-dragging onto Netlify Drop, or by pushing to the host's repo.

When the real product launches, swap the **AVAILABLE SOON** badge for a
**DOWNLOAD** button and link to the latest release (e.g. the GitHub release
or a hosted installer URL). The page is intentionally minimal so this swap
is a 2-line edit.
