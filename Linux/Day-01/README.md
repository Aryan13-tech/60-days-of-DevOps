# 🐧 Linux Practice Log — Day 1

**Topic:** File and Directory Management in Linux

---

## 📂 Commands Practiced

### 1. Directory Navigation
- `pwd` — Shows the current working directory.
- `cd ..` — Move up one directory.
- `cd ~` — Go to the home directory.
- `cd /path/to/dir` — Navigate to a specific path.


### 2. Listing Files
- `ls` — List files in the current directory.

  
- `ls -a` — List all files, including hidden ones.
- `ls -l` — List files in long format (permissions, owner, size, etc.).
- `ls -la` — Combination of `-l` and `-a`.

### 3. File Creation
- `touch file1.txt` — Create an empty file.
- `echo "hello, linux" > file2.txt` — Create a file with content.
- `echo "hidden file" > .hiddenfile` — Create a hidden file.

### 4. Directory Creation
- `mkdir testdir` — Create a new directory.
- `mkdir temp_dir` — Another example of directory creation.

### 5. Copying Files and Directories
- `cp file1.txt file1_copy.txt` — Copy a file.
- `cp file2.txt testdir/` — Copy a file into a directory.
- `cp -r testdir testdir_copy` — Recursively copy a directory.

### 6. Moving and Renaming
- `mv file1.txt newname.txt` — Rename a file.
- `mv newname.txt testdir/` — Move a file to another directory.
- `mv testdir_copy new_testdir` — Rename a directory.
- `mv oiginal_file.txt ./original_file1.txt` — Fix filename typo and rename.

### 7. Deleting Files and Directories
- `rm original_file1.txt` — Delete a file.
- `rm -i file2.txt` — Delete a file interactively (asks confirmation).
- `rm -r testdir` — Remove a directory and its contents.
- `rm -rf temp_dir` — Forcefully remove a directory without confirmation.
- `rm .hiddenfile` — Delete a hidden file.

### 8. Error Handling and Typos
You encountered intentional/accidental typos like:
- `cp filw2.txt` → “No such file or directory”
- `mv newname.txtx` → “Cannot stat...”
  
These helped you understand Linux error feedback — a key part of learning.

---

## ✅ Key Takeaways
- Linux commands are **case-sensitive**.
- Use `ls -a` to view hidden files starting with `.`.
- The `~` symbol refers to your **home directory**.
- `rmdir` only removes **empty directories**.
- Use `rm -r` or `rm -rf` for deleting non-empty directories.
- Always **double-check filenames** before moving or deleting.

---

## 🧠 Summary
Today’s session focused on mastering:
- Basic navigation  
- File/directory creation and management  
- Copy, move, rename, and remove operations  
- Understanding error messages

---
