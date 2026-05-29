# Revert and Reset Commits

Sometimes we may make a wrong commit. Git provides commands to move back to a previous commit.

> Use `git reset` only when the changes are not pushed to GitHub.

---

## Reset to a Previous Commit

```bash
git reset commit-id
```

Moves the current branch to the specified commit.

---

## Types of Reset

### Soft Reset

```bash
git reset --soft commit-id
```

- Removes commits from history.
- Keeps changes in the staging area.
- Files are not deleted.

---

### Mixed Reset (Default)

```bash
git reset --mixed commit-id
```

or

```bash
git reset commit-id
```

- Removes commits from history.
- Keeps changes in the working directory.
- Changes are removed from the staging area.

---

### Hard Reset

```bash
git reset --hard commit-id
```

- Removes commits from history.
- Removes changes from the staging area.
- Removes changes from the working directory.

Use carefully because the changes are deleted.

---

## View Commit History

```bash
git log --oneline
```

Displays commit history in short form.

---

## Recover a Reset Commit

```bash
git reflog
```

Displays the history of HEAD movements.

Even if a commit is removed using `git reset`, its commit ID can usually be found using `git reflog`.

---

## Restore a Commit Using Reflog

```bash
git reset --hard commit-id
```

Use the commit ID from `git reflog` to restore the commit.

---

## Summary

- `--soft` → keeps changes in staging area.
- `--mixed` → keeps changes in working directory.
- `--hard` → removes changes completely.
- `git reflog` helps recover commits that were reset.
