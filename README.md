# GenZ Resort: one-page website

Static site (HTML + CSS, no build step, no JavaScript).

## Edit
Search `REPLACE` in `index.html`. Colours are at the top of `styles.css`.

Replace: WhatsApp number (`234XXXXXXXXXX`), phone, address, `[City]`, `[nearby attraction]`,
room prices/names/amenities, photos in `images/`, Google Maps iframe and directions link,
Instagram/TikTok handles (`yourhandle`), domain (`www.example.com` in index.html, robots.txt, sitemap.xml),
FAQ policies, `images/share.png` (1200x630).

## Test locally
Open `index.html`, or run `python3 -m http.server 8000` and visit http://localhost:8000

## Deploy
1. `git init && git add . && git commit -m "GenZ Resort site"`
2. Push to a new GitHub repo.
3. Vercel: Add New Project, import the repo, Framework Preset "Other", leave build/output blank, Deploy.
4. Add your custom domain in Vercel, then update the domain in the files above.
