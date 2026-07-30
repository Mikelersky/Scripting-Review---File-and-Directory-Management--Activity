# Scripting Review - File and Directory Management Activity

## Overview

This repository contains my Bash scripting activity for creating and managing directories and files automatically using a shell script.

The activity demonstrates basic Linux file and directory management commands and the use of Bash scripting to automate repetitive tasks.

## Objectives

- Create directories using `mkdir`
- Create files using `touch`
- Set execute permissions using `chmod`
- Execute a Bash script
- Verify the generated directory structure using `find`
- Verify created files using `ls` 

## Technologies Used

- Bash
- MSYS2 (UCRT64)
- VirtualBox
- Windows 11

## Files

| File | Description |
|------|-------------|
| `script101.sh` | Bash script that creates the required directory structure |
| `Activity2_Queddeng.pdf` | Documentation of the activity with screenshots and outputs |

## How to Run

```bash
chmod +x script101.sh
./script101.sh
```

## Expected Output

```
Directory structure created successfully!
```

## Directory Structure

```
OS
├── P1
├── P4
│   ├── ReadMe1.txt
│   └── ReadMe2.txt
└── Network
    ├── P2
    │   └── ReadMe1.txt
    └── P3
        └── ReadMe2.txt

Script
├── P1
│   └── ReadMe1.txt
└── P3
```

## Author

**John Michael Queddeng**

MIT-1A
