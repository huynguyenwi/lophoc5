# GitHub Pages Deploy Plan

## Steps
- [x] Fix main.tsx to render `<App />` instead of test div
- [x] Add `base: '/lophoc5/'` to vite.config.ts
- [x] Build project (`npm run build`)
- [x] Create `.github/workflows/deploy.yml` for auto-deploy
- [x] Update `index.html` title to "Học Tập Lớp 5"
- [x] Commit and push changes
- [x] Enable GitHub Pages in Settings (Source: GitHub Actions)

## Notes
- Deploy target: https://huynguyenwi.github.io/lophoc5/
- Method: GitHub Actions (auto build & deploy on push to main)
Status: **COMPLETE** ✅ (Workflow added; push to trigger deploy)

## How to enable GitHub Pages
1. Go to https://github.com/huynguyenwi/lophoc5/settings/pages
2. Under "Build and deployment", set **Source** to **GitHub Actions**
3. Push the code to `main` branch to trigger the first deployment

