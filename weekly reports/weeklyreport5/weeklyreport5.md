---
name: adriel zachariah
class: cis 106
---

# Question 1: Definitions

**mkdir** - creates a directory or directories
- mkdir classwork
- Relative: mkdir classwork/hw1
- Absolute: mkdir ~/classwork/hw1

---

**touch** - creates files, can be used with absolute path or relative path
- touch notes.txt
- Creating multiple files: touch notes.txt test.py
- Relative: touch /Documents/Notes
- Absolute: touch ~/Documents/Notes

---

**rm** - removes files, needs option -r to remove directories
- rm notes
- rm -r Documents/classwork (removes non-empty directory)

---

**rmdir** - removes empty directories
- rmdir Documents/notes

---

**mv** - moves directories and can rename them
- mv Documents/notes.txt Downloads (moves from one directory to another)
- mv notes.txt notes1.txt (renames the file in the same directory)
- mv Documents/notes.txt Downloads/notes1.txt (moves the file and renames it in one command)

---

**cp** - copies files or directories to another location
- cp Documents/notes.txt Downloads
- cp -r Documents/homework Downloads (-r copies a direatory)

---

**ln** - creates a hard link, can be used to create a soft link using -s
- ln file Documents/LFile
- ln -s file Documents/SFile (soft link)

---

**man** - shows the manual of a shell command
- man pwd (brings up the manual of the pwd command which shows its parameters and its usage)

---

# Question 2: Brace Expansion 
Brace expansion {} is a bash features that allows the user to form strings or groups of strings to use in arguments in commands. This feature lets you do things like create or remove multiple files or directories in a single command, such that you do not need to run multiple commands to do the task.
