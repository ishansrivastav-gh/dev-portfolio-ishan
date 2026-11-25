# Details missing from the resume

The template fields below could not be filled from the resume, or were filled with a placeholder. Fix them in `portfolio.config.json`, then re-run `node scripts/build-data.mjs`.

## Placeholders I used (please check)
| Field | Current value | What is needed |
|---|---|---|
| `identity.domain` | `ishansrivastav.dev` | Your real domain, or `ishansrivastav-gh.github.io` if you use GitHub Pages |
| `identity.tagline` | `full-stack, applied gen ai.` | Your own 3-6 word tagline |
| `identity.terminalUser` | `ishan` | Handle shown in the terminal prompt |
| `projects[].url` | your GitHub profile | The real repo or live-demo link for each project |
| `wall.json` / `wall.txt` | short illustrative snippets I wrote | Real code: run `node scripts/build-data.mjs --fetch-github` to pull it from your repos |
| `github-snapshot.json` | empty (0 stars, 0 contributions) | Run `--fetch-github` for your real stats |

## Not in the resume (template needs or supports these)
- **Repository names**: exact GitHub repo names for Insightx360, Drone Simulator, Stock Predictor, Bank Management System (also for `githubRepo` and the "wall" of code).
- **Live links**: Vercel URL for Insightx360; demo links for the other projects.
- **Project screenshots**: images for `projects[].shots` (put them in `site/shots/`, e.g. `shots/insightx360.png`).
- **Work history**: only Deloitte virtual internships were listed. Exact dates, and any other internships/jobs. Education is shown as a "work" entry because the template has no education section.
- **Talks / events**: the template has a talks section with map coordinates; none in the resume, so it is empty. Hackathon (2nd prize) details: event name, place, date, photos, link.
- **Extra links**: X/Twitter, blog, Medium, LeetCode, Kaggle, Hugging Face, etc. (add to `links`).
- **Quantified outcomes**: users, metrics, tech details per project (resume has none), for the `long` descriptions.
- **Location in the footer/bio**: confirm "Lucknow" or your SRM location (Chennai area).
- **Custom logo** (optional): replace the SVG path in `favicon.svg`, `index.html`, `site/index.html` and `MARK` in `site/wheel.js`.
- **Optional face intro**: `face.mp4` / `face.webm` / `face-track.json` (see `scripts/build-face.py`).
- **Resume PDF** (optional): if you want a download link, add the file and a link entry.

## Deliberately left out of the public site
- Your phone number (9839334813). Public portfolios get scraped; add it only if you want it.
- Class X/XII marks, certifications and skills lists: the template has no sections for them. Mention them in `about.bio` or as extra work/project entries if wanted.
