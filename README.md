# Dubai Creative Meetups — website

Single-file static site for https://dubaicreativemeetups.com.

- `index.html` — the whole site (hand-crafted, no build step).
- `images/` — event photos pulled from the community's own Instagram
  (@dubaicreativemeetups). ig-04, ig-06, ig-11 are event flyers, unused.
- `CNAME` — custom domain for GitHub Pages.

## The one thing to configure
`WHATSAPP_NUMBER` near the bottom of `index.html` — digits only,
international format without "+", e.g. `971501234567`. While empty, all
WhatsApp buttons fall back to Instagram DMs.

## Deploy (GitHub Pages)
Push to the `main` branch of the GitHub repo that has Pages enabled
(deploy from branch, root). DNS at GoDaddy: apex A records →
185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153,
`www` CNAME → `<github-user>.github.io`.
