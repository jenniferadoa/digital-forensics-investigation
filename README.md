# digital-forensics-investigation

## Objective
Conduct a simulated digital forensic investigation using forensic tools to identify, preserve, and analyse digital evidence.

## Tools
- Autopsy
- SHA256 hashing
- Windows/Linux command line

## Investigation Areas
- File analysis
- Deleted files
- File metadata
- Browser activity
- Timeline analysis
- Evidence integrity

  ## Finding 1 - Excel File Metadata

Autopsy identified an Excel file named `excel.xls`.

- File type: Microsoft Excel
- Size: 5,632 bytes
- Location: Administrator/Templates
- Created: 9 November 2009
- Modified: 14 April 2008

The file was examined using Autopsy's File Metadata and Text views. No conclusion of data theft can be made from this file alone.

## Finding 2 - PowerPoint File Metadata

Autopsy identified a PowerPoint file named `powerpnt.ppt`.

- File type: Microsoft PowerPoint
- Size: 12,288 bytes
- Location: Administrator/Templates
- Status: Allocated

The file metadata was examined in Autopsy. This file alone does not provide evidence of data theft.

## Status
In progress.
