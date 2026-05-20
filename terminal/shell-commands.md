# Must-Know Shell Commands

## 1. echo

### Definition
The `echo` command is used to print text or values in the terminal.

### Syntax

```bash
echo text
```

### Example

```bash
echo Hello
```

### Output

```text
Hello
```

---

### Example with Variables

```bash
num1=5
num2=4

echo $((num1 + num2))
```

### Output

```text
9
```

---

### Running `.sh` Files

```bash
bash test.sh
```

This command is used to run shell script files.

---

## 2. pwd

### Definition
`pwd` stands for:

```text
Print Working Directory
```

It prints the path of the current working directory.

### Syntax

```bash
pwd
```

### Example Output

```text
/home/adi/projects
```

---

## 3. whoami

### Definition
The `whoami` command prints the current username.

### Syntax

```bash
whoami
```

### Example Output

```text
adi
```
