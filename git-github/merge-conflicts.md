# How to Resolve Merge Conflicts

## What is a Merge Conflict?

A merge conflict occurs when two branches modify the same line in the same file and Git cannot decide which change to keep.

---

## When Does a Conflict Occur?

Example:

- Branch A changes line 10.
- Branch B also changes line 10.

When merging both branches, Git cannot automatically resolve the changes.

---

## Merge a Branch

```bash
git merge branch-name
```

### Example

```bash
git merge conflict
```

---

## Check Branches

```bash
git branch
```

Displays all available branches.

---

## View Branch Graph

```bash
git log --oneline --graph --all
```

Shows branch history and merge points.

---

## Resolve Conflict in VS Code

When a conflict occurs, VS Code provides options:

### Accept Current Change

Keeps the current branch change.

### Accept Incoming Change

Keeps the incoming branch change.

### Accept Both Changes

Keeps both changes.

---

## Complete the Merge

After resolving the conflict:

```bash
git add .
```

```bash
git commit
```

This creates the merge commit and completes the merge.

---

## Conflict During Pull

A conflict can also occur when pulling changes from a remote repository.

```bash
git pull
```

If the same line was modified locally and remotely, Git may create a conflict.

---

## Abort a Merge

```bash
git merge --abort
```

Cancels the merge process and returns the repository to its previous state.

Use this when you are not ready to resolve the conflict.

---

## Tips

- Pull changes regularly.
- Communicate with teammates before changing the same code.
- Resolve conflicts carefully instead of blindly accepting changes.
