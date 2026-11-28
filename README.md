# Cerberus website

Static site, no build step. Pages: index, privacy, terms, security, support. Assets: style.css, dog.svg (hero), bg.svg (fixed background), fonts/ (Orbitron and Manrope, SIL OFL).

## Publish on GitHub Pages
1. Create a NEW PUBLIC repo named `cerberus` (keep the app source repo private).
2. Put the contents of this folder at the repo root and push to `main`.
3. Repo Settings > Pages > Source: "Deploy from a branch" > `main` / `/ (root)` > Save.
4. After a minute the site is at https://petedjenkinsauthor.github.io/cerberus/
   Privacy policy URL for Play: https://petedjenkinsauthor.github.io/cerberus/privacy.html

Termux:
```
git clone https://github.com/peteDJenkinsAuthor/cerberus.git
cp -r site/. cerberus/ && cd cerberus
git add -A && git commit -m "Cerberus site" && git push
```
