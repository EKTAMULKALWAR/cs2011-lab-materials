# 🛠️ CS2011 Lab Setup Guide

This setup guide will help you prepare your development environment for CS2011 labs. By following these steps, you'll be ready to write, edit, and run Java code using Bash and Brackets on macOS.

---

## ✅ What You'll Set Up

- Terminal navigation using Bash
- Class project folder (`cs2011-lab`)
- Java installation (via Homebrew or Adoptium)
- Brackets editor installation
- Basic Bash commands for file handling

---

## 📁 1. Create Your Class Folder

Avoid placing code in Downloads. Use a safe and organized location:

```bash
cd ~/Documents
mkdir cs2011-lab
cd cs2011-lab
```

## 🐚 2. Basic Bash Commands

| Command             | Description                     |
|---------------------|---------------------------------|
| `pwd`               | Print current directory         |
| `ls`                | List files and folders          |
| `cd foldername`     | Change directory                |
| `mkdir foldername`  | Make a new folder               |
| `touch file.java`   | Create a file                   |
| `cat file.java`     | Show file contents              |
| `mv a.java b.java`  | Rename or move a file           |
| `rm file.java`      | Delete a file                   |


## ☕ 3. Install Java
Option A: macOS with Homebrew
```bash
brew install openjdk@17
```
Option B: Manual (macOS & Windows)
Download and install from https://adoptium.net

Verify installation:
``` bash
java -version
```

## ✏️ 4. Install Brackets Editor
Go to: https://brackets.io

Download & install

Open Brackets → File → Open Folder → select cs2011-lab

🎨 Optional: Customize Terminal (macOS)
Go to Terminal > Settings > Profiles

Choose a theme or import one (e.g., Dracula)

Set your favorite as Default

## ℹ️ Notes
Don’t use Git Bash on macOS — use the default Terminal or iTerm2.

Keep all your CS2011 work inside cs2011-lab for easy access.


Created by Ekta Mulkalwar – Graduate TA, CS2011





