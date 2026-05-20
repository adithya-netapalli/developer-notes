# Basics of Vim and Nano Editor

## Nano Editor

### Definition
Nano is a simple terminal-based text editor.

It is beginner-friendly and easy to use.

---

## Opening a File in Nano

```bash
nano fileName
```

---

## Example

```bash
nano notes.txt
```

This command opens `notes.txt` for editing.

---

## Saving and Exiting Nano

### Exit Nano

```text
Ctrl + X
```

After pressing `Ctrl + X`, Nano asks:

```text
Save modified buffer?
```

Options:
- `Y` → Yes
- `N` → No
- `Ctrl + C` → Cancel

---

# Vim Editor

## Definition

Vim is a powerful terminal-based text editor.

Vim stands for:

```text
Vi Improved
```

It is the improved version of the `vi` editor.

---

## Opening a File in Vim

```bash
vim fileName
```

---

## Example

```bash
vim app.js
```

---

## Vim Modes

### 1. Normal Mode
Used for:
- navigation,
- commands,
- deleting,
- copying.

### 2. Insert Mode
Used for typing and editing text.

Press:

```text
i
```

to enter insert mode.

---

## Exit Insert Mode

Press:

```text
Esc
```

---

## Important Vim Commands

### Save File

```vim
:w
```

### Quit Vim

```vim
:q
```

### Save and Quit

```vim
:wq
```

---

## Summary

Nano is simple and beginner-friendly, while Vim is more powerful and advanced for terminal editing.
