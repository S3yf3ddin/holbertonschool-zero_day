# git

![Language](https://img.shields.io/badge/Languages-Bash%20%7C%20C%20%7C%20JavaScript-blue?style=flat-square)
![Git](https://img.shields.io/badge/Git-Workflow%20Practice-orange?style=flat-square&logo=git)

## Description

This directory contains sample source files organized by programming language.  
It is used to practice core **Git workflows** — staging, committing, branching, and keeping the repository up to date.

---

## Directory Structure

```
git/
├── README.md          ← This file
├── bash/
│   ├── best           ← Prints "This School is so cool!"
│   └── school         ← Prints "School"
├── c/
│   └── c_is_fun.c     ← C source file
├── js/
│   ├── index.js       ← JavaScript file
│   └── main.js        ← JavaScript file
└── up_to_date         ← Contains the git pull command
```

---

## Files

### 🐚 bash/

#### `best`

```bash
#!/bin/bash
echo "This School is so cool!"
```

**Usage:**
```bash
bash git/bash/best
# Output: This School is so cool!
```

---

#### `school`

```bash
#!/bin/bash
echo "School"
```

**Usage:**
```bash
bash git/bash/school
# Output: School
```

---

### 🔵 c/

#### `c_is_fun.c`

An empty C source file created to demonstrate tracking new files with Git.

---

### 🟡 js/

#### `index.js` / `main.js`

Empty JavaScript source files created to demonstrate how Git tracks multiple files across different languages in the same repository.

---

### 🔄 up_to_date

```
git pull
```

This file contains the `git pull` command as its content.  
It is used to demonstrate keeping a local repository synchronized with the latest remote changes.

---

## Git Commands Used

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new local repository |
| `git add <file>` | Stage a file for commit |
| `git commit -m "message"` | Commit staged changes with a message |
| `git push` | Push commits to the remote repository |
| `git pull` | Fetch and merge remote changes into the local branch |
| `git status` | Show the working tree status |
| `git log` | Show commit history |

---

## Author

**S3yf3ddin** — [GitHub Profile](https://github.com/S3yf3ddin)
