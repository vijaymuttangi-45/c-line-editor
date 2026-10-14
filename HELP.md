# Simple Line Editor in C — Help Guide

## 1. Overview

The Simple Line Editor is a command-line application developed in C. It allows users to create and edit a text document using commands.

## 2. How to Compile and Run

Open the terminal in the folder containing `p1.c`.

Compile the program:

```bash
gcc p1.c -o line_editor.exe
```

Run the program in Windows PowerShell:

```powershell
.\line_editor.exe
```

Type `h` to display the available commands.

## 3. Supported Commands

### 1. Insert a Line — `i`

**Syntax:**
```text
i <line_number> <text>
```

Inserts text at the specified line number.

**Example:**
```text
i 1 Hello Vijay
```

### 2. Delete a Line — `d`

**Syntax:**
```text
d <line_number>
```

Deletes the specified line.

**Example:**
```text
d 2
```

### 3. Display the Document — `p`

Displays all lines in the current document.

**Example:**
```text
p
```

### 4. Save the Document — `s`

**Syntax:**
```text
s <filename>
```

Saves the current document to a file.

**Example:**
```text
s activity7-test.txt
```

### 5. Open a File — `o`

**Syntax:**
```text
o <filename>
```

Opens and loads a document from an existing file.

**Example:**
```text
o activity7-test.txt
```

### 6. Search for a Word — `f`

**Syntax:**
```text
f <word>
```

Searches the document for the specified word.

**Example:**
```text
f Vijay
```

### 7. Replace Text on One Line — `r`

**Syntax:**
```text
r <line_number> <old_text> <new_text>
```

Replaces the specified text on one line.

**Example:**
```text
r 1 Hello Hi
```

### 8. Replace Text Throughout the Document — `R`

**Syntax:**
```text
R <old_text> <new_text>
```

Replaces matching text throughout the document.

**Example:**
```text
R Hello Hi
```

### 9. Count Lines, Words, and Characters — `c`

Displays the number of lines, words, and characters in the document.

**Example:**
```text
c
```

### 10. Undo the Last Change — `u`

Restores the previous document state when an undo backup is available.

**Example:**
```text
u
```

### 11. Display Help — `h`

Displays the available commands and their syntax.

**Example:**
```text
h
```

### 12. Quit the Editor — `q`

Exits the line editor.

**Example:**
```text
q
```

## 4. Example Session

```text
i 1 Hello Vijay
i 2 Activity 7 Line Editor
p
s activity7-test.txt
c
q
```

## 5. Notes

- Enter commands at the editor's `>` prompt.
- Use valid line numbers when inserting or deleting lines.
- The file must exist before it can be opened.
- Save your document to preserve your changes.
- The undo command restores the previous document state when a backup is available.

