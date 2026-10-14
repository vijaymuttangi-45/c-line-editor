# Line_editor

# Line Editor

A simple C-based line editor that lets you:

- insert lines
- delete lines
- display the document
- save to a file
- load from a file
- search text
- replace text
- undo the last change

## Features

- Command-line interface
- Works in C using arrays
- Lightweight and beginner-friendly

## How to compile

```bash
gcc -Wall -Wextra -std=c11 line.c -o line
```
# Simple Line Editor in C

## Project Description

A command-line text editor developed in C that allows users to insert, delete, display, search, replace, save, and load text lines.

## Student Details

- **Name:** Vijay Muttangi
- **Course:** CSIT
- **Activity:** Activity 7 – Build a Simple Line Editor in C

## Features

- Insert and delete lines
- Display the document
- Save and load text files
- Search for words
- Replace text on a single line or throughout the document
- Count lines, words, and characters
- Undo the last change
- Display command help

## Requirements

- GCC C compiler
- Windows PowerShell or another compatible terminal

## Compile and Run

Compile:

```bash
gcc p1.c -o line_editor.exe
```

Run on Windows PowerShell:

```powershell
.\line_editor.exe
```

## Example Commands

```text
i 1 Hello Vijay
i 2 Simple Line Editor
p
c
s activity7-test.txt
o activity7-test.txt
h
q
```

## Documentation

Refer to [HELP.md](HELP.md) for command syntax and examples.

## Repository

https://github.com/vijaymuttangi-45/c-line-editor