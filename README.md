# tswebley-apex-redirect

Apex redirect: `tswebleyllc.com` to `https://www.tswebleyllc.com` (path kept) via GitHub Pages.
GoDaddy forwarding does not answer HTTPS, so the apex A records point here instead.

DNS at GoDaddy:
- apex `A` 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `www` CNAME `tswebley.pages.dev` (the real site, Cloudflare Pages project `tswebley`)

Public because GitHub Pages free tier requires it. No secrets here.
