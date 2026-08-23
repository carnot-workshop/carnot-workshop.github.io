# Carnot 2026 — workshop site

Live at <https://carnot-workshop.github.io/>

One self-contained page. `index.html` holds all CSS, JavaScript, the logo and the
illustrations inline; the only external request is Google Fonts.

## Files

- `index.html` — the whole site
- `og-image.png` — link preview image for Slack, email and social
- `favicon.png` — browser tab icon (also inlined in index.html)
- `.nojekyll` — serve files as-is, no Jekyll processing

## Publishing

This repo is named `carnot-workshop.github.io`, so GitHub Pages serves it at the
organization root. Settings -> Pages -> Source: **Deploy from a branch**, branch
`main`, folder `/ (root)`.

## Currently unlisted

`index.html` carries `<meta name="robots" content="noindex, nofollow">`, so the
page is reachable by anyone with the link but is kept out of Google and Bing.
Link previews in email and Slack still work.

**To launch publicly:** delete that one `<meta name="robots">` line (it sits under
a clearly marked comment block near the top of `index.html`) and commit. Nothing
else changes. Allow a few days for search engines to pick the page up.

Note this is discretion, not security: the repository and the organization are
public, and the URL is guessable from the org name. Do not put anything in here
that would be a problem for a stranger to read.

## Moving to carnot.unm.edu

1. Add a file named `CNAME` at the repo root containing exactly `carnot.unm.edu`
2. Ask UNM IT for a DNS CNAME record: `carnot` -> `carnot-workshop.github.io`
3. Settings -> Pages -> Custom domain: `carnot.unm.edu`, Save, then tick **Enforce HTTPS**

No content changes needed. Once the domain is live, edit the `og:image` line in
`index.html` to the absolute URL (`https://carnot.unm.edu/og-image.png`) so link
previews resolve for people who aren't on the site.

## Editing

Everything is in `index.html` — open it in the repo, click the pencil icon, edit,
commit. The site rebuilds in under a minute.

To add a speaker portrait, find that speaker's card and replace the
`<div class="avatar">…</div>` with `<img src="portraits/name.jpg" alt="…">`.
There is a comment above each one marking the spot.

## Maintainers

Denis Seletskiy (University of New Mexico) · Masaru Kuno (University of Notre Dame) ·
Peter Pauzauskie (University of Washington / PNNL)
