# Total Concepts Advertising — Website

Marketing site for **Total Concepts Advertising** (Greater Fort Wayne). Static, single-page, self-contained HTML. Built and managed by Creative Tone Media.

- **Live domain:** https://totalconcepts.co (owned by Total Concepts, in their GoDaddy)
- **Hosting:** Vercel (Creative Tone Media account, managed service) — auto-deploys on push to `main`
- **Stack:** Plain HTML/CSS/JS, no build step. Google Fonts is the only external dependency.

## Files
| File | Purpose |
|------|---------|
| `index.html` | The entire site (inline CSS + JS) |
| `vercel.json` | Clean URLs + security headers |
| `robots.txt` / `sitemap.xml` | SEO / Google Search Console |

## Editing
Edit `index.html`, commit, push. Vercel redeploys in ~20 seconds. No build.

## Contact form
Submits via [Web3Forms](https://web3forms.com) (no backend). Leads email to
`info@creativetonemedia.com`, cc Tracy + Kelly. **Setup:** paste a Web3Forms access
key into the `access_key` hidden field in `index.html`.

## Handoff
To move fully to Total Concepts later: transfer this repo + the Vercel project. The
domain already lives in their GoDaddy, so nothing there changes.
