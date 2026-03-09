# 📦 Backup

> Python script to **flatten** a folder structure by moving all files from subfolders into a single target directory with deduplicated filenames.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📂 **Flatten** | Moves all files from nested subfolders to one target folder |
| 🔢 **Deduplication** | Renames duplicates (e.g., `file.txt` → `file_1.txt`, `file_2.txt`) |
| 📝 **Configurable** | Edit `source_directory` and `target_directory` in the script |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **Runtime** | Python 3.x |
| **Dependencies** | None (stdlib only) |

---

## 🚀 Usage

1. Edit the script to set paths:
   ```python
   source_directory = "C:/users/admin/pictures"
   target_directory = "f:/media"
   ```

2. Run:
   ```bash
   python Backup.py
   ```

---

## 📁 Project Structure

```
Backup/
├── Backup.py      # Main flatten script
└── README.md
```

---

<p align="center">
  <sub>📦 Gorstak Utilities</sub>
</p>
