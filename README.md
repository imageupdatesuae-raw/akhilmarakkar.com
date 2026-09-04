# akhilmarakkar.com

Personal writing site. Jekyll on GitHub Pages — nothing to build locally.

## Add a post
Create `_posts/YYYY-MM-DD-short-title.md` starting with:

    ---
    title: "Your title"
    tags: [life]
    ---

Write Markdown below it, commit, push. Live in about a minute.
Or on WhatsApp: "Sam, new post: <title> — <text>".

## Change the look
`assets/style.css` (colours are the `--` variables at the top).
Home page intro: `index.html`. Site name/description: `_config.yml`.

## Domain
`CNAME` holds `akhilmarakkar.com`. DNS lives at Cloudflare (registered under
marakkarakhil@gmail.com): four A records on the apex —
185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153 —
plus CNAME `www` → `<github-user>.github.io`. All DNS-only (grey cloud), NOT proxied,
or GitHub's HTTPS certificate never issues.
Then repo Settings → Pages → Custom domain → akhilmarakkar.com → Enforce HTTPS.
