# 🔗 Understanding Inodes, Hard Links, and Soft Links in Linux

This guide explains the difference between **inodes**, **hard links**, and **soft (symbolic) links** in a simple and practical way — with examples you can try on your Linux system.

---

## 📁 What is an Inode?

An **inode** is a data structure used in Linux/Unix filesystems that stores **metadata** about a file:

- File permissions (read/write/execute)
- Owner and group
- File size
- Timestamps (created/modified/accessed)
- File type (regular file, directory, etc.)
- Disk block pointers (where the file data is stored)

> ⚠️ **Inodes do NOT store the file name or path**. Filenames are stored in directory entries that point to the inode.

---

## 🧱 What is a Hard Link?

A **hard link** is an **alternate name** for the same file. It points directly to the **inode**, not the file name.

### ✅ Key Properties:
- Points to the **same inode** as the original
- File content is **shared**
- Still works if the original file is deleted
- Cannot link to **directories**
- Cannot span across **file systems**

### 🔧 Example:
```bash
ln original.txt hardlink.txt
