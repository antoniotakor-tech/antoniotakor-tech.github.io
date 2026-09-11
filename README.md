# antoniotakor-tech.github.io

My personal site — live at **https://antoniotakor-tech.github.io**

I start where there is no product yet: find the real problem, test it with the people who have
it, then build something that works.

## What's on it

- **How I work** — the process, and where I come into it
- **Work** — four projects. Click one to see how it actually went
- **How I work with people** — the three ways I usually get brought in
- **Contact** — a form that opens your own mail app, no backend

## Stack

Plain HTML, CSS and JavaScript. No framework, no build step, no dependencies — deliberately,
so one person can keep maintaining it. Hosted on GitHub Pages.

- Google Fonts: Archivo, Space Grotesk
- English / Italian, switchable — one page, one dictionary in `i18n.js`
- Reveal animations via `IntersectionObserver`, with a failsafe so content can never stay hidden
- Respects `prefers-reduced-motion`, works down to 375px
- No analytics, no cookies, no third-party scripts, nothing stored anywhere

## Run it locally

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Contact

**Antonio Frungillo** — Amsterdam
[antoniotakor@icloud.com](mailto:antoniotakor@icloud.com)
