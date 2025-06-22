# Automated Backup Script with Logging


# Description
A Python script that automates the process of backing up files/folders by compressing them into timestamped ZIP archives. It also logs each backup with file names and backup time for reference or audits.

# Features
- Automatic ZIP backups of files or folders
- Timestamps added to filenames
- Log file (`backup.log`) with detailed info
- Simple and customizable script


# Technologies
- Python 3.x (standard library only)


# Getting Started

# Create and activate a virtual environment
```bash
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

No external dependencies required
Run the app
python backup_script.py
Requirements
Uses only built-in Python modules:
os, shutil, zipfile, datetime, logging
