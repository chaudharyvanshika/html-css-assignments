# Assignment 4 – Git Commits

## Objective
To understand Git configuration, repository creation, staging, committing, and maintaining a Git commit history.

## 1. Git Identity Configuration

Checked my Git username and email using:

```bash
git config --global user.name
git config --global user.email
```

Git identity was already configured on my computer.

## 2. Repository Creation

Created a new repository named `html-css-assignments`.

```bash
mkdir html-css-assignments
cd html-css-assignments
git init
git branch -M main
```

## 3. Commit 1 – Add README

Created a README file containing the project overview.

```bash
git add README.md
git commit -m "docs: add README with project overview"
```

## 4. Commit 2 – Add Assignments 1–5

Added the first five assignment files and committed them.

```bash
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup & git assignments (1-5)"
```

## 5. Commit 3 – Add HTML Basics Assignments 6–10

The following commands will be used after completing Assignments 6–10.

```bash
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments (6-10)"
```

## 6. View Commit History

Used the following command to check the commit history:

```bash
git log --oneline
```

## Result

Successfully configured Git, created the repository, added the README, and committed Assignments 1–5. Commit 3 will be completed after preparing Assignments 6–10.

## Commit 1 – Add README

Created a README file containing the project overview.

```powershell
git add README.md
git commit -m "docs: add README with project overview"
```

## Commit 2 – Add Assignments 1–5

The assignment files will be added after preparing Assignments 1–5.

## Commit 3 – Add HTML Basics Assignments

HTML assignments 6–10 will be added after they are completed.

## Result

Successfully configured Git, created a new local repository, and made the first commit. The remaining commits will be completed as the assignment files are prepared.