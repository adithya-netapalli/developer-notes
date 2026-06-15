# How to Create & Merge Branches

## View Commit History

```bash
git log
```

Displays complete commit history.

---

## Short Commit History

```bash
git log --all --oneline
```

Shows commit history in short form.

---

## Check Current Branch

```bash
git branch
```

Displays all branches.

- The current branch is highlighted with `*`.

---

## Create a Branch

```bash
git branch branchName
```

### Example

```bash
git branch about
```

Creates a new branch called `about`.

---

## Switch Between Branches

```bash
git checkout branchName
```

### Example

```bash
git checkout about
```

Switches to the `about` branch.

---

## Branch Behavior

When a new branch is created:
- it contains all commits and code from the current branch,
- but changes made later in the new branch are not available in the old branch unless merged.

---

## Delete a Branch

```bash
git branch --delete branchName
```

### Example

```bash
git branch --delete contact
```

A branch cannot be deleted while currently inside that branch.

Switch to another branch before deleting it.

---

## View Branch Graph

```bash
git log --oneline --all --graph
```

Displays commit history as a graph in the terminal.

---

# Merging Branches

## Merge Command

```bash
git merge branchName
```

Merges the given branch into the current branch.

### Example

```bash
git merge about
```

---

## Merge Commit

When merging:
- Git may automatically create a new commit,
- and generate a merge commit message.
