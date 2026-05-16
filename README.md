# mrcookiemstr.github.io

This repository publishes **[https://mrcookiemstr.github.io/](https://mrcookiemstr.github.io/)** (GitHub user site).

## How it works

- The site must live in a repository named **`mrcookiemstr.github.io`** under your user — that is [how GitHub maps the apex `*.github.io` URL](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites).
- **`main`** is the default branch; static files in the root (`index.html`, `style.css`, …) are served as the homepage.
- Other projects keep their own repos and can be linked here (for example [no_rfcable](https://github.com/mrcookiemstr/no_rfcable) under `/no_rfcable/`).

## Edit locally

```bash
git clone https://github.com/mrcookiemstr/mrcookiemstr.github.io.git
cd mrcookiemstr.github.io
# edit index.html / style.css, then:
git add -A && git commit -m "Update site" && git push
```

Changes appear on Pages after a short deploy delay.
