GitHub Pages publish directory for helm

Contents:
- index.html
- zh-CN.html
- update-manifest.json
- RELEASE_NOTES.md
- site-assets/

Build steps:
1. corepack pnpm build
2. npm run prepare:site-assets
3. npm run prepare:github-pages

Publish options:
- Push only this directory to a dedicated public Pages repo, or
- Publish this directory from a gh-pages branch

No source code is required for Pages hosting.
