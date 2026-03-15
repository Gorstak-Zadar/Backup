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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
