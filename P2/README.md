# P2 — Portfolio repository and initial commit

## Aim
Create a Git repository for a portfolio and record its initial version.

## Procedure
```bash
mkdir portfolio
cd portfolio
git init
echo "# My Portfolio" > README.md
git status
git add README.md
git commit -m "Initial commit: add portfolio README"
git log --oneline
```

Configure identity if Git requests it:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
Use the email associated with your GitHub account if you intend to publish commits.

## Expected result
A local Git repository with one initial commit. Verify it with `git log --oneline`.
