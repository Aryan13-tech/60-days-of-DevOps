# 🐧 Linux Learning - Day 3

---



## 🧩 Topic: Examining File Contents

In this session, I learned how to **inspect and read file contents** in Linux using three essential commands — `cat`, `head`, and `tail`.

---

## 🧠 Commands Practiced

### 1. `cat` – View Complete File Content
Used to display the full contents of a file in the terminal.

```bash
cat /home/labex/project/manuscript_v1.txt
```

### 2. head – View the Beginning of a File

Used to display the first few lines of a file.
By default, it shows the first 10 lines, but we can specify how many to show.

```bash
head -n 2 /home/labex/project/manuscript_v2.txt
```

### 3. tail – View the End of a File

Used to display the last few lines of a file.
By default, it shows the last 10 lines, but we can limit it to the last line.

```bash
tail -n 1 /home/labex/project/manuscript_v1.txt
tail -n 1 /home/labex/project/manuscript_v2.txt
```

---

## ⚙️ Requirements Followed

Used only the commands: cat, head, and tail.

Did not modify the file contents.

Practiced reading specific parts of text files efficiently.

---

## 📘 Summary

Today’s practice improved my understanding of how to view and analyze text files in Linux.
These commands are very helpful for quickly checking file data without opening a text editor.
