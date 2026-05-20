# Command Line File Management

## touch Command

### Definition
The `touch` command is used to create files.

---

## Syntax

```bash
touch fileName
```

---

## Example

```bash
touch index.html
```

---

## Creating Multiple Files

```bash
touch style.css app.js notes.txt
```

This command creates multiple files at the same time.

---

## mkdir Command

### Definition
The `mkdir` command is used to create directories (folders).

---

## Syntax

```bash
mkdir folderName
```

---

## Example

```bash
mkdir projects
```

---

## cp Command

### Definition
The `cp` command is used to copy files from one location to another.

---

## Syntax

```bash
cp source destination
```

---

## Example

```bash
cp app.js backup/
```

This command copies `app.js` into the `backup` folder.

---

## mv Command

### Definition
The `mv` command is used to:
- move files,
- rename files.

---

## Move Example

```bash
mv app.js projects/
```

---

## Rename Example

```bash
mv app.js script.js
```

---

## rm Command

### Definition
The `rm` command is used to permanently delete files.

---

## Syntax

```bash
rm fileName
```

---

## Example

```bash
rm notes.txt
```

---

## rmdir Command

### Definition
The `rmdir` command is used to remove empty directories.

---

## Example

```bash
rmdir testFolder
```

---

## rm -r Command

### Definition
The `rm -r` command is used to delete folders recursively.

It deletes:
- folder,
- subfolders,
- files inside them.

---

## Example

```bash
rm -r projects
```

⚠️ This permanently deletes the folder and its contents.

---

## rm -f Command

### Definition
The `rm -f` command forcefully deletes files without confirmation.

---

## Example

```bash
rm -f notes.txt
```

---

## Summary

These commands are used for creating, copying, moving, renaming, and deleting files and folders in the terminal.
