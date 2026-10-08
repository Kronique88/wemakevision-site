# WeMakeVision

One-page company site for wemakevision.com, hosted on GitHub Pages.

## Files

| File | Purpose |
| --- | --- |
| index.html | The whole site: markup, styles and a few lines of script. No build step. |
| CNAME | Custom domain for GitHub Pages (wemakevision.com). |
| .nojekyll | Tells GitHub Pages to serve files as-is. |
| robots.txt, sitemap.xml | Search engine hints. |

## Editing

Edit index.html and push to main. GitHub Pages redeploys automatically.

Sections, in order: Hero, Services, Products, Process, About (CEO), Contact.

## Custom domain DNS

At your DNS provider for wemakevision.com:

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| AAAA | @ | 2606:50c0:8000::153 |
| AAAA | @ | 2606:50c0:8001::153 |
| AAAA | @ | 2606:50c0:8002::153 |
| AAAA | @ | 2606:50c0:8003::153 |
| CNAME | www | GITHUB_USERNAME.github.io |

Then in the repository: Settings > Pages > Custom domain = wemakevision.com, and tick "Enforce HTTPS" once the DNS check passes.
