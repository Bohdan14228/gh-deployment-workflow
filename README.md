# gh-deployment-workflow

**Project:** [https://roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)  

# 🌐 GitHub Pages Deployment Workflow

This project automatically updates the website on **GitHub Pages** every time the `index.html` file changes in the **main** branch.

🔗 **Live site:** [https://<username>.github.io/gh-deployment-workflow/](https://bohdan14228.github.io/gh-deployment-workflow/)

---

## ⚙️ How it works
- Workflow triggers on every push to `main` when `index.html` changes  
- GitHub Pages is configured to deploy directly from the `main` branch (root folder)

---

## 🚀 Run it
1. Push any changes to `index.html`  
2. GitHub Actions workflow runs automatically  
3. Your site updates at the GitHub Pages URL

---

## 🧩 Workflow file
Located at:  
`.github/workflows/deploy.yml`
