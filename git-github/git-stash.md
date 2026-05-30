# Git Stash

## What is Git Stash?

Git Stash is used to temporarily save uncommitted changes without creating a commit.

It allows us to switch branches and continue other work without losing current progress.

## Create a Stash

```bash
git stash
```

Temporarily stores the current changes.

### Add a Message

```bash
git stash save "message"
```

### Example

```bash
git stash save "navbar changes"
```

## View All Stashes

```bash
git stash list
```

Displays all available stashes.

## Apply a Stash

```bash
git stash apply
```

Restores the latest stash.

### Apply a Specific Stash

```bash
git stash apply stash@{0}
```

Restores the selected stash.

## Pop a Stash

```bash
git stash pop
```

Restores the stash and removes it from the stash list.

## Delete a Stash

```bash
git stash drop stash@{0}
```

Deletes the selected stash.

## Stash Conflicts

A conflict may occur when applying a stash if the same code has been modified after the stash was created.

Resolve the conflict and commit the changes.

## Summary

- `git stash` → save changes temporarily.
- `git stash list` → view all stashes.
- `git stash apply` → restore a stash.
- `git stash pop` → restore and remove a stash.
- `git stash drop` → delete a stash.
