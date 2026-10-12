# Mocho — mocho.dev

Static one-page website for **mocho.dev**, ready for GitHub Pages.

## Files

- `index.html` — complete website (HTML + CSS + a tiny JavaScript snippet)
- `favicon.svg` — site icon
- `CNAME` — tells GitHub Pages to use `mocho.dev`
- `robots.txt` — basic crawler configuration

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `mocho-site`.
2. Upload all files in this folder to the root of the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. In **Custom domain**, enter `mocho.dev`.
7. In Name.com DNS, configure the GitHub Pages records for the apex domain and `www`.
8. After DNS verification succeeds, enable **Enforce HTTPS**.

## Before making the site public

The page intentionally describes Mocho as an **independent, student-led, early-stage initiative** and includes a disclosure that it is not affiliated with or endorsed by ESPOL.

The contact button currently uses `contact@mocho.dev`. Configure that mailbox or forwarding before relying on it for incoming messages.

## Suggested DNS records for GitHub Pages

Always verify the current values in GitHub's official documentation before changing DNS.

Typical apex A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Typical `www` CNAME:

- `moisesvillenam.github.io`

Do not add the repository name to the CNAME target.
