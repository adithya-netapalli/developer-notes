# What is a Prompt in the Terminal?

## Definition

A prompt is the text shown in the terminal before a command is typed.

It indicates that the terminal is ready to accept commands.

---

## Example Prompt

```bash
adi@ubuntu:~$
```

---

## What Information a Prompt Can Show

A terminal prompt may display:
- username,
- system name,
- current directory,
- special symbols.

---

## PS1

### Definition

`PS1` is the primary prompt variable in the terminal.

It controls the main command prompt appearance.

---

## Example

```bash
echo $PS1
```

This command displays the current primary prompt format.

---

## PS2

### Definition

`PS2` is the secondary prompt variable.

It appears when a command continues to the next line.

---

## Example

```bash
echo $PS2
```

---

## Summary

A prompt is used to show that the terminal is ready to receive commands from the user.
