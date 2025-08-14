# Advanced File Linux Commands

---

## **1️⃣. File Manipulation Commands**

### ⇢ **`touch`** – Create or Update File Timestamps

```bash
# Create an empty file
touch file1.txt

# Update timestamp of an existing file
touch existing.txt

# Create multiple files at once
touch file2.txt file3.txt
```

---

### ⇢ **`cp`** – Copy Files and Directories

```bash
# Copy a file
cp source.txt destination.txt

# Copy to another directory
cp source.txt /path/to/destination/

# Copy directory recursively
cp -r dir1 dir2

# Preserve file attributes (timestamps, permissions)
cp -p source.txt backup.txt
```

---