# drinkingc0ffee.com

Static coming-soon page. Host it for free on GitHub Pages.

## Preview locally

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish (GitHub Pages + Namecheap)

1. Create a public GitHub repo and push this folder.
2. Repo → **Settings** → **Pages** → deploy from `main` / root.
3. In Namecheap → **Advanced DNS**, remove parking/redirect records, then add:
   - A `@` → `185.199.108.153`
   - A `@` → `185.199.109.153`
   - A `@` → `185.199.110.153`
   - A `@` → `185.199.111.153`
   - CNAME `www` → `YOURUSER.github.io`
4. In GitHub Pages, set custom domain to `drinkingc0ffee.com` and enable HTTPS when the cert is ready.

DNS usually settles in 15–60 minutes.
