# Autopsy Disk Forensics Investigation

## Overview

This project demonstrates a basic digital forensics investigation using **Autopsy** on a Windows environment.

The investigation focuses on analyzing a controlled virtual disk image and examining file-system artifacts, deleted files, browser activity, metadata, and file hashes.

## Objectives

- Analyze a virtual disk image using Autopsy
- Examine the file system and stored files
- Identify and recover deleted files
- Analyze browser-related artifacts
- Review file metadata and timestamps
- Examine file hashes
- Document forensic findings
- Generate a final forensic investigation report

## Tools & Technologies

- **Operating System:** Windows
- **Forensic Tool:** Autopsy
- **Evidence Format:** VHD (Virtual Hard Disk)
- **File System:** NTFS
- **GitHub:** Project documentation and report storage

## Investigation Methodology

1. Created a controlled virtual disk image.
2. Added fictional test files and browser activity.
3. Deleted selected test files.
4. Created a forensic case in Autopsy.
5. Added the VHD as the evidence source.
6. Ran relevant Autopsy ingest modules.
7. Examined file-system artifacts.
8. Investigated deleted files and recovery results.
9. Reviewed browser artifacts.
10. Examined metadata, timestamps, and hashes.
11. Documented relevant evidence.
12. Generated the final forensic investigation report.

## Evidence Analyzed

The investigation used a controlled training disk image:

`Malini_Evidence.vhd`

The evidence contains fictional data created specifically for educational and demonstration purposes.

## Key Areas Investigated

### File System Analysis
Examined files and folders stored within the virtual disk image.

### Deleted File Analysis
Identified deleted files and examined available recovery results.

### Browser Artifact Analysis
Reviewed available browsing history, searches, and download-related artifacts.

### Metadata Analysis
Examined available:

- File names
- File types
- File sizes
- Creation timestamps
- Modification timestamps
- Access timestamps

### Hash Analysis
Reviewed available file hash values to support evidence identification and integrity verification.

## Project Structure

```text
Malini_Autopsy_Project/
│
├── README.md
├── Malini_Autopsy_Disk_Forensics_Report.docx
├── Screenshots/
└── Reports/
