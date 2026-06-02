# cunningplay-com

Static placeholder site for **Cunningplay LLC** (https://cunningplayinc.github.io/cunningplay-com/ or https://cunningplay.com once DNS is configured).

Single-page holding-company landing — names Cunningplay LLC, links to Ashenmarch as the current product, signals incubator intent ("more projects in time").

## Editing

Edit `index.html`, commit, push. GitHub Pages auto-deploys from `main`.

## Custom domain (later)

When ready to serve at `cunningplay.com`:

1. Add a `CNAME` file containing the single line `cunningplay.com`
2. At your domain registrar, point `cunningplay.com` at GitHub Pages:
   - `A` records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `AAAA` records to `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
   - Or a `CNAME` for `www.cunningplay.com` to `cunningplayinc.github.io`
3. In repo Settings → Pages, set custom domain to `cunningplay.com` and tick "Enforce HTTPS"

Until then the github.io URL works fine — pasteable into Stripe, LinkedIn, attorney correspondence, etc.
