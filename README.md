# File Organizer Pro

A Python-based utility to automatically organize messy folders based on file types.

## Features
- **Directory Scanning**: Scans any provided path.
- **File Type Detection**: Detects extensions and matches them to categories.
- **Safe Moving**: Uses `shutil` for reliable file transfers.
- **Categorization**:
    - Images (`.jpg`, `.png`, etc.)
    - Documents (`.pdf`, `.docx`, etc.)
    - Videos (`.mp4`, `.mov`, etc.)
    - Scripts (`.py`, `.js`, etc.)
    - Archives (`.zip`, `.rar`, etc.)
    - Others (Catch-all for unknown types)

## Requirements
- Python 3.x

## Usage
1. Run the script: `python organizer.py`
2. Provide the folder path when prompted.
3. Watch your files get organized!

---
*Note: Always test on a sample folder before running on critical system directories.*
