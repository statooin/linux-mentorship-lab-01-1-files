# Linux Mentorship Lab 01.1: File Management

This repository contains materials for **Lab 01.1**, focusing on the core operations of managing files in a Linux environment. Master the command-line tools required to create, view, modify, and organize files efficiently.

## 🎯 Objectives
The goal of this lab is to build a solid foundation in file manipulation. By the end of this lab, you will be able to:
* Create empty and content-filled files using various methods.
* View and inspect file contents without opening a full editor.
* Move, rename, and copy files across the file system.
* Safely remove files and understand the implications of permanent deletion.
* Understand the difference between hard links and symbolic (soft) links.

## 📋 Core Commands & Utilities

### Creating & Viewing
* `touch` — Create an empty file or update timestamps.
* `cat` — Concatenate and display file content.
* `less` / `more` — View long files page by page.
* `head` / `tail` — View the beginning or the end of a file (useful for logs).

### Manipulation
* `cp` — Copy files (`cp source destination`).
* `mv` — Move or rename files (Linux treats renaming as a move operation).
* `rm` — Remove files (use with caution!).

### Linking
* `ln` — Create a hard link.
* `ln -s` — Create a symbolic (soft) link.

## 🚀 Lab Tasks
1. **Creation**: Create a set of practice files using `touch` and redirect some text into them using `echo > file.txt`.
2. **Inspection**: Use `head` and `tail` to extract specific lines from system configuration files in `/etc`.
3. **Organization**: Create a backup of your work by copying files to a `backup/` directory and renaming the originals.
4. **Linking**: Create a symbolic link to a deeply nested file and verify that it points to the correct location.

## ⚠️ Important Note
In Linux, there is no "Recycle Bin" for the `rm` command in the terminal. Once a file is deleted via the CLI, it is generally unrecoverable for standard users. Always double-check your syntax!

---
*This lab is part of the Linux Mentorship program. Master the files, master the system!*
