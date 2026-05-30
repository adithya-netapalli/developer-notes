# .gitignore File

## What is .gitignore?

The `.gitignore` file is used to tell Git which files and folders should not be tracked.

It is commonly used for:
- `.env` files
- `node_modules`
- temporary files
- generated files

## Create a .gitignore File

```text
.gitignore
```

The file has no name and only an extension.

## Ignore a File

```text
.env
```

Git will stop tracking changes made to this file.

### Example

```text
style.css
```

Ignores `style.css`.

## Ignore a Folder

```text
node_modules/
```

Ignores the entire `node_modules` folder.

## Remove a Tracked File

If a file is already being tracked, adding it to `.gitignore` is not enough.

```bash
git rm --cached fileName
```

### Example

```bash
git rm --cached style.css
```

Removes the file from Git tracking.

## Remove a Tracked Folder

```bash
git rm -r --cached folderName
```

### Example

```bash
git rm -r --cached node_modules
```

Removes the folder from Git tracking.

## Summary

- `.gitignore` prevents files from being tracked.
- Used for sensitive and unnecessary files.
- `git rm --cached` removes tracked files.
- `git rm -r --cached` removes tracked folders.
