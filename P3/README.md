# P3 — Feature-branch Git workflow

## Aim
Practice creating a feature branch, making a change, committing it, and merging it into the main branch.

## Procedure
```bash
git switch -c feature/about-section
```
Create or edit a file, then:
```bash
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
git log --oneline --graph --all
```

If the default branch is named `master`, substitute `master` for `main`. Resolve any merge conflicts by editing the marked file, then stage and commit the resolution.

## Expected result
The feature branch is merged into the main branch and the history shows the change.
