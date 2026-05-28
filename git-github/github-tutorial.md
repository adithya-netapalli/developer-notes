# Complete GitHub Tutorial

## Drawback of Git

When we use:

```bash
git init
```

Git creates a hidden `.git` folder.

This folder stores:
- commit history,
- tracking information,
- version control data.

If the `.git` folder is deleted, the entire Git history and tracking information will be lost.

---

## Online Git Platforms

To store projects safely online, developers use platforms like:

- GitHub
- GitLab
- Bitbucket

---

## Check Remote Repository

```bash
git remote show origin
```

Displays the remote repository connected to the current project.

---

## Connect Local Repository to Remote Repository

```bash
git remote add origin repository-link
```

Connects local project with remote GitHub repository.

---

## Rename Branch

```bash
git branch -M main
```

Renames the current branch to `main`.

---

## Push Code to GitHub

```bash
git push -u origin main
```

Pushes local commits to the remote repository.

---

## git push

```bash
git push
```

Uploads local commits to the remote repository.

---

## Fast Forward Merge

A fast forward merge happens when:
- branch history is linear,
- and no extra merge commit is needed.

---

## Add Collaborators on GitHub

Steps:
- Open repository settings
- Go to collaborators
- Add GitHub username

---

## git pull

```bash
git pull
```

Downloads remote changes to the local repository.

---

## git fetch + git merge

```text
git pull = git fetch + git merge
```

- `git fetch` downloads changes
- `git merge` merges changes into current branch

---

## Useful VS Code Extensions

### Git Graph

Free extension used to visualize Git history.

### GitLens

Popular Git extension with advanced features.
