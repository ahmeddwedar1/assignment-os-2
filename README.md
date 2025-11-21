# Assignment 2 – Process Management in Linux
Operating Systems – CSE233  
Alamein University

---

## 📌 About This Assignment
This project contains the implementation and explanation of Lab 5 tasks related to:
- Creating processes using fork()
- Managing processes (start, stop, pause, continue)
- Understanding the role of the *Linker* and *Loader*
- Compiling multi-file C programs
- Using a Makefile for automatic build
- Preparing documentation and screenshots

---

## 📁 Files Included

| File | Description |
|------|-------------|
| process_creation.c | Example of using fork() to create a child process |
| file1.c | Contains hello() function (used in linker example) |
| file2.c | Calls the function from file1.c |
| simple_program.c | Program used to inspect dynamic libraries with ldd |
| Makefile | Automatically compiles all programs |
| LICENSE | MIT License |
| screenshots/ | Contains screenshots of compilation and execution |
| answers.txt | Written explanations for linker, loader, fork, and process control |

---

## 🧪 Exercises Summary

### 🔹 *1. Process Creation – fork()*
Uses fork() to create a child process and print the PID of both parent and child.

### 🔹 *2. Starting a Process in Background*
Using:
