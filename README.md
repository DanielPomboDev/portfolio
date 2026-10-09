# Daniel G. Pombo — Portfolio

Static single-file portfolio for **Daniel G. Pombo**, Backend Developer / Software Engineer (BSIT, ESSU May 2026).

Live stack: plain HTML + Tailwind CSS (CDN) + Google Fonts. No build step.

## Contents

- `index.html` — entire site (nav, hero, work, about/experience, contact, footer)
- `skills-lock.json` — pinned agent skills (reproducible via `opencode` / agent tooling)
- `.gitignore` — ignores local AI state (`.freebuff/`, `.agents/`, `.opencode/skills/`), secrets, OS/editor junk, build output

## Run locally

Just open the file:

```powershell
start index.html
```

Or serve it (so relative paths / mobile testing work):

```powershell
npx -y serve .
```

## Deploy (Vercel)

This is a static site — deploy as-is:

```powershell
npx -y vercel --prod
```

No build command, output directory is `.`.

## Sections

1. **Hero** — role, location (San Julian, Eastern Samar, open to Manila/NCR), core stack
2. **Work** — SmartLeave (HR leave system), KJV Bible offline app (Tauri)
3. **About / Experience** — BSIT, Junior Developer Intern @ Advanced Thinkers Co. (Jan–May 2026)
4. **Contact** — `danpombo08@gmail.com`, `09511830414`

## Contact

- GitHub: https://github.com/DanielPomboDev
- LinkedIn: https://linkedin.com/in/daniel-pombo
- Email: danpombo08@gmail.com

© 2026 Daniel G. Pombo
