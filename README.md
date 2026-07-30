# Bash Directory Structure Generator

## Overview
This project contains a Bash script that automatically generates a predefined directory and file structure.

The script demonstrates the use of basic Bash commands such as:

- mkdir
- touch
- chmod
- find
- ls


## Directory Structure

```
.
├── OS
│   ├── P1
│   ├── P4
│   │   ├── ReadMe1.txt
│   │   └── ReadMe2.txt
│   └── Network
│       ├── P2
│       │   └── ReadMe1.txt
│       └── P3
│           └── ReadMe2.txt
└── Script
    ├── P1
    │   └── ReadMe1.txt
    └── P3
```

## Requirements

- Bash
- Linux, macOS, or MSYS2 (Windows)

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/bash-directory-structure-generator.git
```

2. Navigate to the project.

```bash
cd bash-directory-structure-generator
```

3. Give execute permission.

```bash
chmod +x script101.sh
```

4. Run the script.

```bash
./script101.sh
```

## Expected Output

```
Directory structure created successfully!
```

## Verify the Result

```bash
find .
```

```bash
ls OS/P4
```

```bash
cat OS/P4/ReadMe1.txt
```

## Files

- `script101.sh` - Bash script that generates the directory structure.
- `README.md` - Project documentation.

## Author

John Michael Queddeng

Master of Information Technology (MIT) Student

Mariano Marcos State University
