# d-mlawncare.com Redirect

This repository is a GitHub Pages redirect from:

- `https://d-mlawncare.com`
- `https://www.d-mlawncare.com`

to:

- `https://dmlandscapingkings.com/`

All old URLs redirect to the new homepage (root). This is intentional so outdated page paths
like `/sod-installation` or `/testimonials` do not land on 404s on the new site.

## DNS setup (Wix DNS)

For apex `d-mlawncare.com`:

- `A` -> `185.199.108.153`
- `A` -> `185.199.109.153`
- `A` -> `185.199.110.153`
- `A` -> `185.199.111.153`

For `www.d-mlawncare.com`:

- `CNAME` -> `<your-github-username>.github.io`

## GitHub Pages setup

1. Publish this repo to GitHub.
2. Open repo `Settings -> Pages`.
3. Source: `Deploy from a branch`.
4. Branch: `main` / folder: `/ (root)`.
5. Custom domain: `d-mlawncare.com`.
6. Enable `Enforce HTTPS` after DNS resolves.
