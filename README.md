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

## Public and indexed

As of v0.18 the page is publicly searchable — the `<meta name="robots">` line
that kept it out of Google and Bing has been removed. Allow a few days for
search engines to pick it up.

`index.html` also carries `Event` structured data (JSON-LD) so the workshop is
eligible for Google's event listings, and `carnot-2026.ics` lets visitors add
the dates to their calendar.

## Moving to carnot.unm.edu

1. Add a file named `CNAME` at the repo root containing exactly `carnot.unm.edu`
2. Ask UNM IT for a DNS CNAME record: `carnot` -> `carnot-workshop.github.io`
3. Settings -> Pages -> Custom domain: `carnot.unm.edu`, Save, then tick **Enforce HTTPS**

Once the domain is live, update the absolute URLs in `index.html` — `og:url`,
`og:image`, and the `url`/`image` fields in the JSON-LD block — from
`https://carnot-workshop.github.io/` to `https://carnot.unm.edu/`. After any
change to those tags, run the URL through LinkedIn's Post Inspector
(<https://www.linkedin.com/post-inspector/>) to force a re-scrape; LinkedIn
caches link previews for weeks otherwise.

## Editing

Everything is in `index.html` — open it in the repo, click the pencil icon, edit,
commit. The site rebuilds in under a minute.

To add a speaker portrait, find that speaker's card and replace the
`<div class="avatar">…</div>` with `<img src="portraits/name.jpg" alt="…">`.
There is a comment above each one marking the spot.

## Maintainers

Denis Seletskiy (University of New Mexico) · Masaru Kuno (University of Notre Dame) ·
Peter Pauzauskie (University of Washington / PNNL)
