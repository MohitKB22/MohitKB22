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

## Step 4: Enable Contribution Snake

1. In your `MohitKB22` repo, create `.github/workflows/` folder
2. Upload `snake.yml` (from `.github/workflows/` in this package) there
3. Go to **Settings → Actions → General → Workflow Permissions**
4. Select **"Read and write permissions"** → Save
5. Go to **Actions tab** → Run `Generate Contribution Snake` manually
6. After it runs, an `output` branch will be created with your snake SVGs
7. In `README.md`, this line will work:
   ```
   https://raw.githubusercontent.com/MohitKB22/MohitKB22/output/github-contribution-grid-snake-dark.svg
   ```

---

## Step 5: GitHub Widgets — No Setup Needed
All widgets use external services that auto-pull your GitHub data:
- `github-readme-stats` — stats & top languages
- `github-readme-streak-stats` — streak counter
- `github-readme-activity-graph` — contribution graph
- `github-profile-trophy` — trophy display
- `komarev.com/ghpvc` — profile view counter

All will auto-populate once the README is live.

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
