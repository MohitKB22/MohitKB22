# 🚀 Setup Guide — Mohit Barse GitHub Profile

## Step 1: Create the Profile Repository
1. Go to GitHub → New Repository
2. Name it **exactly** `MohitKB22` (must match your GitHub username)
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

---

## Step 2: Upload the README
1. Open the generated `README.md` from this package
2. Replace the contents of your repo's README with this file
3. Commit directly to `main`

---

## Step 3: Upload SVG Assets
1. In your `MohitKB22` repo, create a folder: `assets/`
2. Upload all files from `assets/svg/` into `assets/` in your repo
3. Update any `![img](assets/...)` references in the README to match

   Alternatively, host them on a CDN or use GitHub raw URLs:
   ```
   https://raw.githubusercontent.com/MohitKB22/MohitKB22/main/assets/01-hero-banner.svg
   ```

---

## Step 4: Workflows (stats cards + contribution snake)

Two workflows in `.github/workflows/` keep the dynamic parts of the README fresh:

- `readme-stats.yml` — generates the github-readme-stats cards (stats, top languages, pinned repos) into `profile/` daily.
- `snake.yml` — generates the contribution snake into the `output` branch every 12 hours.

Both declare `contents: write` themselves and also run automatically when their workflow file is pushed. To run them on demand: **Actions tab → select the workflow → Run workflow**.

Optional: to include private contributions in the stats card, create a classic PAT with `repo` and `read:user` scopes and add it as the repository secret `GRS_TOKEN` (**Settings → Secrets and variables → Actions**).

---

## Step 5: External Widgets — No Setup Needed
These services pull your GitHub data on request:
- `streak-stats.demolab.com` — streak counter
- `github-readme-activity-graph` — contribution graph
- `komarev.com/ghpvc` — profile view counter

---

## Step 6: Personalize Your README

Replace these placeholders before publishing:

| Placeholder | Replace With |
|---|---|
| `MohitKB22` | Your GitHub username |
| `mohitbarse2230@gmail.com` | Your email |
| `mohit-b-9a997b301` | Your LinkedIn path |
| `mohitkb22` | Your Twitter/X handle |
| Project repo URLs | Your actual repo URLs |
| Certification status | Your actual status |

---

## Optional: Add WakaTime Coding Stats

1. Sign up at https://wakatime.com
2. Install the IDE plugin
3. Add to README:
   ```markdown
   ![WakaTime Stats](https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME_USERNAME&theme=tokyonight&hide_border=true)
   ```

---

## File Structure of This Package

```
github-profile-complete/
├── README.md                     ← Main profile README
├── .github/
│   └── workflows/
│       └── snake.yml             ← Contribution snake automation
├── assets/
│   └── svg/
│       ├── 01-hero-banner.svg
│       ├── 02-open-to-work-banner.svg
│       ├── 03-collab-banner.svg
│       ├── 04-recruiter-card.svg
│       ├── 05-ai-dashboard.svg
│       ├── 06-current-learning-banner.svg
│       ├── 07-current-focus-banner.svg
│       ├── 08-featured-projects-banner.svg
│       ├── 09-certifications-showcase.svg
│       ├── 10-architecture-gallery.svg
│       └── 11-footer-banner.svg
└── docs/
    ├── setup-guide.md            ← This file
    └── widgets-config.md         ← GitHub widget URLs and config
```
