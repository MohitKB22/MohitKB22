# GitHub Widgets Configuration
# Mohit Barse — MohitKB22

---

## 1. GitHub Stats Card
```markdown
![Mohit's GitHub Stats](https://github-readme-stats-sigma-five.vercel.app/api?username=MohitKB22&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github)
```
**Placement:** After Featured Projects  
**Theme:** tokyonight | **Custom:** replace sigma-five with vercel.app if rate limited

---

## 2. Top Languages Card
```markdown
![Top Languages](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=MohitKB22&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&exclude_repo=fork1,fork2)
```
**Placement:** Next to GitHub Stats (use side-by-side with HTML div)

---

## 3. GitHub Streak Stats
```markdown
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=MohitKB22&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)
```
**Placement:** Below GitHub Stats  
**Alternative URL:** https://streak-stats.demolab.com/?user=MohitKB22&theme=tokyonight&hide_border=true

---

## 4. Contribution Activity Graph
```markdown
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=MohitKB22&theme=tokyo-night&hide_border=true&area=true&point=38bdf8&line=818cf8&color=e2e8f0)
```
**Placement:** Standalone full-width row

---

## 5. GitHub Trophies
```markdown
![Trophies](https://github-profile-trophy.vercel.app/?username=MohitKB22&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=6)
```
**Placement:** After Certifications section  
**Options:** column=4 for compact, column=7 for wide screens

---

## 6. Profile Summary Cards
```markdown
![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MohitKB22&theme=tokyonight)
```
**Placement:** At top of stats section  
**All cards available at:** https://github.com/vn7n24fzkq/github-profile-summary-cards

---

## 7. Visitor Counter
```markdown
![Visitors](https://komarev.com/ghpvc/?username=MohitKB22&label=Profile%20Views&style=for-the-badge&color=0f172a&labelColor=1e3a5f)
```
**Placement:** Hero section, beside followers badge

---

## 8. Metrics Widget (lowlighter/metrics)
Advanced self-hosted widget. Requires GitHub Actions setup.
```yaml
# .github/workflows/metrics.yml
name: Metrics
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: MohitKB22
          template: classic
          base: header, activity, community, repositories
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_languages: yes
          plugin_languages_indepth: yes
          plugin_topics: yes
          plugin_topics_limit: 20
```
**Placement:** Advanced Stats section  
**Full docs:** https://github.com/lowlighter/metrics

---

## Side-by-Side Layout (Stats + Languages)
```markdown
<div align="center">
  <img height="175" src="https://github-readme-stats-sigma-five.vercel.app/api?username=MohitKB22&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="175" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=MohitKB22&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</div>
```
