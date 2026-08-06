# Predictopia diagrams (draw.io)

**Tool of record:** [diagrams.net](https://app.diagrams.net/)  
**Rule:** Orthogonal connectors preferred; keep labels readable.

## Core set

| File | Content |
|------|---------|
| `01-system-context.drawio` | Actors + external systems (Supabase, CricketData, WhatsApp) |
| `02-component-blocks.drawio` | Web app, API, prediction / scoring / prize modules |
| `03-deployment.drawio` | Free-tier: Vercel + Supabase + CricketData |
| `04-sequence-predict.drawio` | One-tap pick → cutoff enforcement → reveal |
| `05-sequence-scoring.drawio` | On-demand result fetch → score → leaderboard |
| `06-user-journey-admin.drawio` | Create pool → share → approve → season end |
| `07-user-journey-member.drawio` | Invite → join → predict → leaderboard |

## Open

1. https://app.diagrams.net/ → **Open Existing** → pick a `.drawio` file  
2. Or VS Code: **Draw.io Integration** (`hediet.vscode-drawio`)

```bash
cd ~/projects/predictopia/docs/diagrams
open -a "Google Chrome" https://app.diagrams.net/
```

Export SVG/PNG into `export/` when refreshing the public docs site.

## Source

Derived from wiki Architecture, User Journeys, and Solution Sketch (2026-03 / refreshed 2026-07-28).
