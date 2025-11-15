# 🐧 Linux Learning - Day 2

---

## 📘 1. Introduction
This README documents my **Day 2 progress** in learning Linux commands using **LabEx**.  
The focus of the day was on **file manipulation**, **directory management**, **content viewing**, and **file comparison** — all essential skills for system administrators and DevOps engineers.

---

## ⚙️ 2. Learning Objectives
The main goals for today’s session were:
- Master copying and renaming files/directories.  
- Learn how to delete files/directories safely.  
- Explore commands for viewing and comparing file contents.  
- Understand Linux’s **case-sensitive file system**.  


---

## 📂 3. Tasks and Commands Practiced


### 🗂️ A. Copying Files and Directories
Learned how to use the `cp` command to duplicate files and folders.

```bash
cp ~/.zshrc ~/Desktop/zshrc-copy
cp -r ~/Code ~/Desktop/
```
Explanation:

cp → copies files.

-r → recursively copies all files and subdirectories.

### ✏️ B. Renaming Files and Directories

Practiced renaming using the mv command.

```bash

mv ~/Desktop/zshrc-copy ~/Desktop/zshrc-move
mv ~/Desktop/Code ~/Desktop/Code-move
```

### 🗑️ C. Removing Files and Directories

Used the rm command to delete files and directories permanently.

```bash
rm ~/Desktop/zshrc-move
rm -r ~/Desktop/Code-move

```
Explanation:

rm → removes files permanently.

-r → required for deleting directories and their contents.

### 📄 D. Viewing File Contents

Explored multiple commands to view and inspect file contents efficiently.

```bash

cat /tmp/hello
cat -n /tmp/hello
head -n1 /tmp/hello
head -c1 /tmp/hello
tail -n1 /tmp/hello
tail -c2 /tmp/hello
```
Example Output:
```bash
Hi,
I am Labby!
```
Explanation:

cat → view the entire file.

cat -n → shows line numbers.

head → displays top lines or characters.

tail → displays bottom lines or characters.

-n → number of lines.

-c → number of characters.

### ⚖️ E. Comparing Files and Directories

Learned how to compare files and directories using the diff command.

```bash

diff file1 file2

```
Example Output:
```bash

  1c1
< this is file1
---
> this is file2
```
Explanation:

diff → compares files line-by-line.

-r → recursively compares directories.

Linux treats Code and code as different directories (case-sensitive).

---

## 🧠 4. Key Takeaways

Linux file and directory names are case-sensitive.

cp, mv, and rm are core commands for file management.

head and tail help read specific parts of files.

diff highlights differences between files or directories.

Always be cautious with rm — it permanently deletes files.

---
 
## 🚀 5. Next Goals

In Day 3, I will learn about:

File permissions using chmod.

File ownership using chown.

Viewing permissions using ls -l.

---

