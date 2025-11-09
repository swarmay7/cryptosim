Deploy to GitHub Pages (quick):
1. Create a new repository on GitHub (public), e.g., `cryptocurrency-simulator`.
2. Upload all files from this ZIP to the repository root (use "Add file -> Upload files").
3. Commit changes.
4. Go to Settings -> Pages -> Source -> select branch `main` and folder `/ (root)`, Save.
5. After a minute, visit: https://<your-username>.github.io/<repo-name>/

Git (optional):
  git init
  git add .
  git commit -m "Initial commit"
  git branch -M main
  git remote add origin https://github.com/<your-username>/<repo-name>.git
  git push -u origin main
