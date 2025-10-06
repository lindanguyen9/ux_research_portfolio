## Publish via GitHub Pages (Minimal Setup)

1) Create a new GitHub repo (public or private with Pages enabled).

2) In this project root, run:
```
git init
git add .
git commit -m "Add UX Research portfolio"
git branch -M main
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```

3) Enable Pages:
- GitHub → Repo → Settings → Pages
- Source: Deploy from branch
- Branch: main, Folder: /docs
- Save

4) Your site URL will be shown on the Pages screen (usually https://<user>.github.io/<repo>/)

Site structure used by Pages:
- `/docs` contains web pages (`index.md`, case studies, resume, contact)
- `_config.yml` selects a theme (`jekyll-theme-cayman`)

To edit content, update the markdown files and push to `main`; Pages redeploys automatically.


