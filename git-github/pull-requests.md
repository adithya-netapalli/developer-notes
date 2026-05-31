# Pull Requests

## What is a Pull Request?

A Pull Request (PR) is used to request merging changes from one branch into another branch.

It allows code to be reviewed before merging into the main branch.

## Why Use Pull Requests?

- Protect important branches.
- Review code before merging.
- Improve team collaboration.

## Create a New Branch

```bash
git checkout -b bug-fix
```

Creates and switches to a new branch.

## Push Branch to GitHub

```bash
git push -u origin bug-fix
```

Uploads the branch to GitHub.

## Create a Pull Request

Steps:

1. Open the repository on GitHub.
2. Go to Pull Requests.
3. Click **New Pull Request**.
4. Select source and target branches.
5. Click **Create Pull Request**.

## Review and Approval

The repository owner or reviewer can:

- Review the changes.
- Approve the Pull Request.
- Merge the Pull Request.

## Merge Pull Request

After approval, the Pull Request can be merged into the target branch.

## Branch Protection

GitHub allows protecting branches such as `main`.

Protected branches:
- cannot be directly modified,
- require Pull Requests before merging.

## Summary

- Pull Request (PR) is used to merge changes through review.
- PRs help protect important branches.
- Protected branches require approval before merging.
- Pull Requests are commonly used in team projects.
