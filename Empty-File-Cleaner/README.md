# Empty File Cleaner

Automation script that periodically scans a directory and deletes all empty files (0 bytes) to free up inodes.

## How to run

python AutomationScript1.py DirectoryName
## Flags

- `--h` : Help information
- `--u` : Usage instructions

## Features

- Scans all subdirectories using os.walk()
- Deletes empty files automatically
- Creates timestamped log files
- Runs periodically using schedule module
