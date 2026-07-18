# vcatreya-git.github.io

Personal profile site — resume + side projects.

## Local preview

```bash
cd ~/Projects/vcatreya-git.github.io
open index.html
# or
python3 -m http.server 8080
# → http://localhost:8080
```

## PDF resume

On the site: **Download PDF** (or nav **PDF**).

Browser: Print → **Save as PDF**. Use A4 or Letter; keep backgrounds if you want chip colors.

## Publish (GitHub Pages)

```bash
cd ~/Projects/vcatreya-git.github.io
git add .
git commit -m "Add personal profile: resume + PMRocket"
# create repo once:
gh repo create vcatreya-git.github.io --public --source=. --remote=origin --push
# then: GitHub → Settings → Pages → Deploy from branch main / root
```

Site URL: **https://vcatreya-git.github.io/**

## Content to fill

Experience, education, and some skills on `index.html` still use `[bracket]` placeholders. Replace with real content (or hand a PDF/Word resume to an agent to paste in).
