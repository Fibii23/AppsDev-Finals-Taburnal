# AppsDev-Finals-Taburnal

# Event Registration System

## Overview
The Event Registration System is a C# Console Application that manages event registration records using file handling only. The system stores data in text files, validates records, generates reports, and logs all operations in an audit file.

This project strictly follows the required specifications:
- Console Application only
- File Handling only
- No Database
- No GUI
- Persistent Storage
- Audit Logging
- Report Generation
- Checksum Validation

---

# Main Features

## 1. Initialize Storage
The system automatically creates the required folders and files during startup if they do not exist.

### Storage Structure
```text
/Data
/Logs
/Reports
events.txt
audit_log.txt
reports.txt