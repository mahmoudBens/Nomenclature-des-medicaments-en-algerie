### Deploy dist to github pages

```bash
cd dist
git init
git config user.email "<github-user-email>"
git config user.name "<github-user>"
git add -A
git commit -m 'deploy'

git remote add origin https://github.com/<github-user>/Nomenclature-des-medicaments-en-algerie.git
git push -f origin master:gh-pages
```