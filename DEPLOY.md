# Publish with GitHub Pages (free)

This site is a static website, so GitHub Pages can host it for free. The workflow in `.github/workflows/pages.yml` publishes the site whenever you push to `main`.

## 1. Create a public repository

1. Sign in or create a free account at [github.com](https://github.com).
2. Create a new **public** repository, for example `owen-kanyemba-portfolio`.
3. Do not add a README, license, or `.gitignore` in GitHub; the site already has its files.

## 2. Push this folder

Open PowerShell in this website folder and run these commands, replacing `YOUR-USERNAME` with your GitHub username and `owen-kanyemba-portfolio` if you used a different repository name:

```powershell
git init
git add .
git commit -m "Add Owen Kanyemba portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/owen-kanyemba-portfolio.git
git push -u origin main
```

Git may open a browser sign-in flow the first time you push. Never share your password or access token in chat.

## 3. Enable Pages

In the GitHub repository, open **Settings → Pages**, set the build and deployment source to **GitHub Actions**, and save. The workflow will publish the site. Future pushes to `main` deploy automatically.

The public address will be:

`https://YOUR-USERNAME.github.io/owen-kanyemba-portfolio/`

The first deployment may take a few minutes. Check the repository's **Actions** tab for deployment status.
