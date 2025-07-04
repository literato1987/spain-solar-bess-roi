# How to Upload This Project to GitHub

Follow these steps to publish your project to a new public GitHub repository:

## 1. Initialize Git (if not already done)
```bash
git init
```

## 2. Add All Files
```bash
git add .
```

## 3. Commit Your Changes
```bash
git commit -m "Initial commit: Spain Solar+BESS ROI model and notebook"
```

## 4. Create a New Repository on GitHub
- Go to https://github.com/new
- Name it (e.g.) `spain-solar-bess-roi`
- Do **not** initialize with a README (you already have one)

## 5. Add the Remote and Push
Replace `<your-username>` and `<repo-name>` with your GitHub username and chosen repository name:
```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

## 6. Share the Link
- Copy the GitHub repository URL and share it on LinkedIn or with collaborators.

---

**Tip:** If you already have a remote set, you may need to update it with:
```bash
git remote set-url origin https://github.com/<your-username>/<repo-name>.git
```

**Done!** Your project is now public and ready for open-source collaboration.
