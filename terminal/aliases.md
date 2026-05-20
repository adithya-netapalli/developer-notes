# Create Aliases for Frequent Commands

## What is an Alias?

An alias is a shortcut name for a long or frequently used command.

It helps save time while working in the terminal.

---

## Alias Syntax

```bash
alias name="command"
```

---

## Example

```bash
alias ll="ls -la"
```

Now instead of typing:

```bash
ls -la
```

we can simply type:

```bash
ll
```

---

## Another Example

```bash
alias reload="source ~/.bashrc"
```

This alias reloads the `.bashrc` file quickly.

---

## Viewing All Aliases

```bash
alias
```

This command displays all existing aliases.

---

## Temporary Aliases

Aliases created directly in the terminal work only for the current session.

After closing the terminal, they are removed.

---

## Permanent Aliases

To make aliases permanent, add them inside:

```text
~/.bashrc
```

Then reload the file using:

```bash
source ~/.bashrc
```

---

## Why Aliases are Useful

Aliases help:
- reduce typing,
- improve productivity,
- simplify long commands.

---

## Summary

Aliases are shortcuts for commands that make terminal usage faster and more efficient.
