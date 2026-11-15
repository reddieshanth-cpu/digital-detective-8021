# Mission 3 — Understand the Operating System

## 1. Task / Objective

The objective of this mission was to explore the operating system, running processes, storage, file paths and permissions, and understand the responsibilities of an operating system.

## 2. Work Completed

- Checked macOS system information.
- Identified the active user account.
- Checked available and used storage.
- Observed system activity.
- Explored running processes using Activity Monitor.
- Understood PID and process management.
- Practised absolute and relative paths.
- Checked file permissions.
- Studied six operating-system responsibilities.

### Task 3.1 — Operating System Exploration

| Information explored | What it tells you | Observation |
|---|---|---|
| Operating system | Identifies the installed OS | macOS |
| Current account | Shows the active account | [redacted] |
| Available storage | Shows used and free storage | Checked using `df -h /` |
| System activity | Shows running system activity | Observed using `top` |

### Task 3.2 — Processes

A process is a program that is currently running on a computer.

PID stands for Process ID. It is a unique number assigned to each running process.

Examples of processes include Google Chrome and Finder. These applications run as processes when they are active.

### Task 3.3 — Paths and Permissions

An absolute path gives the complete location of a file or folder, whereas a relative path gives the location starting from the current directory.

| Permission | Meaning |
|---|---|
| r — Read | Allows reading a file |
| w — Write | Allows modifying a file |
| x — Execute | Allows executing a file |

The `ls -l` command displays file permissions. The owner permissions indicate whether the file owner can read, write or execute the file.

### Task 3.4 — Operating System Responsibilities

| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Manages running programs and CPU time. | Running Chrome and Terminal together. |
| Memory management | Allocates and manages RAM for applications. | Giving memory to a browser. |
| Device management | Controls connected hardware devices. | Managing a keyboard and printer. |
| File management | Organises and manages files and folders. | Saving documents into folders. |
| User interface / shell | Allows users to interact with the computer. | macOS desktop and Terminal. |
| Security and permissions | Protects files and controls access. | File permissions and passwords. |

## 3. Commands / Tools Used

| Command / Tool | Purpose |
|---|---|
| `sw_vers` | Displays macOS version information |
| `whoami` | Displays the active username |
| `df -h /` | Checks available and used storage |
| `top -l 1` | Displays a system activity snapshot |
| `head` | Displays the first lines of output |
| Activity Monitor | Observes running processes |
| `cd` | Changes the current directory |
| `pwd` | Displays the current directory |
| `ls -l` | Displays detailed file information and permissions |

## 4. My Understanding

I learned that an operating system manages the hardware and software resources of a computer. It manages processes, memory, devices, files and security.

I understood that a process is a running program and that every process has a PID. Absolute paths show the complete location of files, while relative paths depend on the current directory.

I also learned that file permissions control whether users can read, write or execute files. These features help the operating system manage resources and protect information.

## 5. Difficulties Faced

Initially, I was confused about the difference between absolute paths and relative paths and how to identify file permissions in Terminal.

## 6. How I Resolved Them

I practised navigating between directories using the `cd` command and checked the current location using `pwd`. I used `ls -l` to understand file permission symbols such as read, write and execute.

## 7. Evidence / Files

- README.md
- macOS system information observations
- Storage information observations
- Process observations from Activity Monitor
- File permission and path observations

## 8. Commit Details

**Commit message:** Document operating system and file management

**Repository:** digital-detective-8021

**Push status:** Pending Git commit and push.

