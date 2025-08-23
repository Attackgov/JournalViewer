# JournalViewer by Attack

**JournalViewer** is a Windows console tool for scanning the NTFS USN Journal to detect file activity such as deleted, replaced, renamed, and created files.  

## Features
- Scan for:
  - Deleted files
  - Replaced files
  - Renamed files
  - Created files
- Spinner animation while scanning
- Opens results in a `.txt` file automatically

## Current Status
- Uses `fsutil` for reading the USN Journal.
- Results are currently output as the plain text CSV values used by fsutil.
- **Upcoming:** Results will be better organized for easier review.

## Requirements
- Windows (admin privileges required)
- Console/Command Prompt

## Usage
1. Run the program as **Administrator**.
2. Select the type of file activity to scan.
3. Enter the file extension to filter results (e.g., `.exe`).
4. Wait for the scan to complete — results will open automatically in a `.txt` file.

---

This tool just simplifies the process of checking journal via cmd.
