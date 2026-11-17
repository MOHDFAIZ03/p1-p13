# P4 — GitHub README and version tags

## Aim
Document a repository and mark a release using a Git tag.

## Procedure
1. Add a README containing the project title, purpose, setup instructions, and usage.
2. Stage and commit it:
   ```bash
   git add README.md
   git commit -m "Document project in README"
   ```
3. Create an annotated version tag:
   ```bash
   git tag -a v1.0.0 -m "First lab release"
   git tag
   ```
4. Push commits and the tag:
   ```bash
   git push origin main
   git push origin v1.0.0
   ```
5. On GitHub, verify the README on the repository page and inspect the tag under Releases or Tags.

## Expected result
A readable GitHub README and a version tag named `v1.0.0`.
