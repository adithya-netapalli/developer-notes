# Git and Version Control

## Check Git Version

```bash
git -v
```

- If Git is not installed, it shows:
```text
git is not recognized as an internal or external command
```

- If installed, it shows the Git version available in the system.

---

## Open Terminal Shortcut

```text
Ctrl + ~
```

Used to open the VS Code terminal quickly.

---

## Initialize Git Repository

```bash
git init
```

This command creates a hidden `.git` folder that helps Git track project changes.

---

## Add Files to Staging Area

### Add Single File

```bash
git add index.html
```

Sends `index.html` to the staging area.

---

### Add All Files

```bash
git add .
```

Sends all files to the staging area.

---

## Check Git Status

```bash
git status
```

Shows the status of all files.

---

## Short Status

```bash
git status -s
```

Displays the status in short form.

---

## Commit Changes

```bash
git commit -m "message"
```

Commits the staged changes with a message.

---

## Configure Git Username and Email

Git requires username and email before making commits.

---

### Check Configured Username

```bash
git config --global user.name
```

---

### Check Configured Email

```bash
git config --global user.email
```

---

### Configure Username

```bash
git config --global user.name "username"
```

---

### Configure Email

```bash
git config --global user.email "email"
```

---

## Commit ID

Every commit has a unique commit ID.

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
