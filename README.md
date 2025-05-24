# GitHub Pages Deployment via GitHub Actions

This project demonstrates a simple Continuous Integration and Deployment (CI/CD) workflow using **GitHub Actions**. Any time the `index.html` file is updated on the `main` branch, the website will automatically be deployed to **GitHub Pages**.

## 🚀 Live URL

[https://<your-username>.github.io/gh-deployment-workflow/](https://<your-username>.github.io/gh-deployment-workflow/)

> Replace `<your-username>` with your GitHub handle.

## 📁 Project Structure

- `index.html`: Static HTML content.
- `.github/workflows/deploy.yml`: CI/CD workflow.
- `README.md`: Project documentation.

## ✅ How It Works

- When you push a change to `index.html` on the `main` branch:
  - GitHub Actions triggers the `deploy.yml` workflow.
  - It builds and deploys the `index.html` to GitHub Pages.
  - The site is published automatically under your GitHub Pages URL.

## 🧠 Concepts Learned

- GitHub Pages Hosting
- GitHub Actions CI/CD
- Workflow Triggers with `paths`
- Static Website Deployment

## 📦 Bonus

Want to go further? Replace `index.html` with output from:
- [Jekyll](https://jekyllrb.com/)
- [Hugo](https://gohugo.io/)
- [Astro](https://astro.build/)

Then build before uploading the artifact.

---

Built with ❤️ and GitHub Actions.

Project website - https://roadmap.sh/projects/github-actions-deployment-workflow
