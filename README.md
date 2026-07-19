# vcatreya-git.github.io

Personal profile site — resume, **PM case studies**, and side projects.

## Case studies

Group PM training work (Team Hashiras), linked from the homepage `#case-studies` section:

| Case study | Path |
|------------|------|
| Blinkit PeakPulse (dark store DSS) | [`case-studies/blinkit-peakpulse/`](./case-studies/blinkit-peakpulse/) |
| Relay — founder-led CRM | [`case-studies/relay-founder-crm/`](./case-studies/relay-founder-crm/) |
| YouTube long-form engagement | [`case-studies/youtube-long-form/`](./case-studies/youtube-long-form/) |

Index: [`case-studies/README.md`](./case-studies/README.md)

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
