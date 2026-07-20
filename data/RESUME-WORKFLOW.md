# Resume workflow

## Files

| File | Purpose | On public site? |
|------|---------|-----------------|
| [`experience-master.md`](./experience-master.md) | Full experience + skills bank | **No** (not linked; raw URL possible if known) |
| [`experience-master-source.pdf`](./experience-master-source.pdf) | Original user dump archive | No |
| `../index.html` | Generic public profile + crisp resume | **Yes** |

## When user pastes a JD

1. Read `experience-master.md` in full (narratives + skills inventory + JD tags).
2. Extract JD: must-haves, nice-to-haves, domain, seniority, keywords.
3. Select roles/bullets/skills from the master that map cleanly — use **Detailed Experience** for depth, not only summary lines.
4. Write a tailored resume (markdown): header, 3–5 line summary, experience (reordered/expanded), skills matched to JD.
5. Rules:
   - **No invention** of experience, metrics, employers, or tools not in the master
   - Prefer **ownership language** (owned, defined, launched, turned around) over aspirational framing
   - Title default: **Agile Product Owner / TPM** unless user specifies otherwise
   - Call out 2–4 transfer bridges only when honest
   - Do **not** claim Spring Boot for 2010 TCS work (use Java/JEE/Spring era-appropriate)
   - Use **CAD** (Change Account Titling) not CAT unless user corrects
   - RTP $1.3–1.4M figure: only if user wants commercial scale emphasized
6. Add a short “Match notes” section: what was emphasized and any JD gaps.

## When updating the public generic resume

1. Edit master first if facts change.
2. Regenerate the crisp cut in `index.html` from the master (length-limited).
3. Do not paste the full skills bank onto the public page.
