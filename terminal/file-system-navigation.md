# Navigating the File System

## cd Command

### Definition
`cd` stands for:

```text
Change Directory
```

It is used to move from one folder to another folder in the terminal.

---

## Syntax

```bash
cd folderName
```

---

## Example

```bash
cd projects
```

This command moves into the `projects` folder.

---

## Parent Directory

```bash
cd ..
```

- `..` means one level above the current folder.
- It moves to the parent directory.

### Example

```bash
cd ..
```

---

## Root Directory

```bash
cd /
```

- `/` represents the root directory.
- It is the top-most directory in Linux file systems.

Using multiple `../` eventually reaches the root directory.

---

## Relative Path

A relative path starts from the current directory.

### Example

```bash
cd projects/react-app
```

---

## Absolute Path

An absolute path starts from the root directory.

### Example

```bash
cd /home/adi/projects
```

---

## Summary

The `cd` command is used to navigate between directories in the terminal.
