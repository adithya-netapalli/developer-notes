
# Git Cherry Pick

## What is Cherry Pick?

Cherry Pick is used when we want to copy a specific commit from one branch to another branch.

Instead of merging the entire branch, only the selected commit is added.

## View Commit History

```bash
git log --oneline --all
```

Displays all commits and their commit IDs.

## Cherry Pick a Commit

```bash
git cherry-pick commit-id
```

### Example

```bash
git cherry-pick f3f123
```

Copies the selected commit to the current branch.

## How it Works

- Switch to the branch where you want the changes.
- Copy the commit ID.
- Run the cherry-pick command.
- Git creates a new commit with the same changes.

## Important Note

Cherry Pick does not merge the entire branch.

Only the selected commit is copied.

## Summary

- `git cherry-pick commit-id` → copies a specific commit.
- Used when only a particular change is needed.
- A new commit is created in the current branch.
