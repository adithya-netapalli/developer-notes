# Understanding `.bashrc` File

## What is `.bashrc`?

`.bashrc` is a configuration file used by the Bash shell.

It stores commands and settings that run automatically whenever a new terminal session starts.

---

## Common Uses of `.bashrc`

- creating aliases,
- setting environment variables,
- customizing terminal behavior,
- running startup commands.

---

## Example

```bash
echo "Running .bashrc"
```

This command can be added inside `.bashrc` to check whether the file executes when the terminal starts.

---

## source Command

### Definition

The `source` command is used to execute the contents of a file in the current terminal session.

---

## Syntax

```bash
source filePath
```

---

## Example

```bash
source ~/.bashrc
```

This command reloads the `.bashrc` file without restarting the terminal.

---

## Why `.bashrc` is Important

The `.bashrc` file helps developers:
- save time,
- automate terminal setup,
- customize workflows.

---

## Summary

`.bashrc` is an important Bash configuration file used to customize and automate terminal behavior.
