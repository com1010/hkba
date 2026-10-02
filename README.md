# HKBA — Hong Kong Blockchain Association 香港區塊鏈協會

Static website for **hkba.net** / **www.hkba.net**, migrated from HKBA.cc (sites.google.com/view/hongkongblockchain).

## Structure
- `index.html` — Home: about, history, university partners, featured leadership, partners, gallery, offices
- `leadership.html` — Full leadership team (66 members)
- `speech.html` — Tony Tong keynote: Web1.0 → Web4.0
- `events.html` — Events & announcements (MOU, AMAs, Fintech Week)
- `web3listing-guide.html` — Web3 listing guideline
- `news.html`, `web3list.html` — member-area placeholders (source content is login-walled)

## Deploy
Push to `main` → connect to Cloudflare Pages → custom domains `hkba.net` + `www.hkba.net`.

## Rebuild
Source extracts are in `../_src/`. People data: `people.json`. Rebuild pages: `python ../build_site.py`.
