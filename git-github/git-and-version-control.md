# Git and Version Control

## What is Version Control?

1. Version Control is a system that tracks changes made to files or code over time.

2. It stores different versions of a project, so developers can see:
- what changed,
- when it changed,
- and who changed it.

3. It helps developers collaborate safely and restore older versions if mistakes happen.

---

## Check Git Version

```bash
git -v
```

- If Git is not installed:
```text
git is not recognized as an internal or external command
```

- If installed, it shows the Git version available in the system.

---

## Open VS Code Terminal

```text
Ctrl + ~
```

Shortcut used to open terminal in VS Code.

---

## Initialize Git Repository

```bash
git init
```

Creates a hidden `.git` folder that helps Git track project changes.

---

## Add Files to Staging Area

### Add Single File

```bash
git add index.html
```

### Add All Files

```bash
git add .
```

---

## Check Status

```bash
git status
```

Shows the status of files.

### Short Status

```bash
git status -s
```

Displays the status in short form.

---

## Commit Changes

```bash
git commit -m "message"
```

Commits staged changes with a message.

---

## Configure Username and Email

Git requires username and email before making commits.

### Check Username

```bash
git config --global user.name
```

### Check Email

```bash
git config --global user.email
```

### Configure Username

```bash
git config --global user.name "username"
```

### Configure Email

```bash
git config --global user.email "email"
```

---

## Commit ID

Each commit has a unique commit ID.

---

## Go to Previous Version

```bash
git checkout commit_id
```

Used to switch to a previous commit version.

---

## Useful VS Code Extension

### GitLens

GitLens helps:
- track changes,
- view commit history,
- improve Git workflow inside VS Code.
