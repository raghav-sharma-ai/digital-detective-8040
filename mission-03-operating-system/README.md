# MISSION 3 — Understand the Operating System

## 1. Task 

The objective of this mission was to understand how an operating system works. I explored system information, storage, running processes, file paths, and file permissions using Terminal.

I also learned about the main responsibilities of an operating system, like managing memory, processes, files, and devices.

## 2. Work completed
- Checked basic system information using Terminal.
- Checked which account was currently active.
- Observed the storage space available on my computer.
- Viewed running processes and learned about their PIDs.
- Learned the difference between absolute and relative paths.
- Checked file permissions using the `ls -l` command.
- Learned about the main responsibilities of an operating system.

### Task 3.1 — Explore the operating system

I used Terminal commands to check information about my computer. These commands helped me understand the operating system, storage, and system activity.

| Information explored | What it tells you | My observation |
|---|---|---|
| Operating system / system details | It shows information about the operating system and the system environment. | I used `uname -a` to view system information. I am using macOS. |
| Current account identity | It shows which user account is currently active in Terminal. | I used `whoami` to check the current account. I have not included the actual username for privacy. |
| Available and used storage | It shows how much storage is used and how much is available. | I used `df -h` to check the storage information. The output showed the used and available space. |
| System activity snapshot | It gives information about running processes and system activity. | I used `top -l 1` to view a snapshot of system activity. |

### Task 3.2 — Understand processes

**What is a process?**

A process is a program that is currently being executed on a computer.
**What does the PID column represent?**

PID stands for Process ID. It is a unique number given to a running process by the operating system. It helps the operating system identify and manage each process.

**Two examples of processes:**

1. A web browser, such as Chrome or Safari.
2. A text editor, such as VS Code.

I used the `ps -ax` command to view the running processes. The output contained a PID column that showed the process IDs.

### Task 3.3 — Understand paths and permissions

A path tells us the location of a file or folder on the computer.

**Absolute path:**

An absolute path gives the full location of a file starting from the root of the filesystem.

Example:

`/Users/[redacted]/desktop/digital-detective-8040/mission-03-operating-system/README.md`

**Relative path:**

A relative path gives the location of a file from the current directory.

Example, when I am inside the repository folder:

`mission-03-operating-system/README.md`

**Difference between absolute and relative paths:**

An absolute path gives the complete location of a file. A relative path depends on the directory where we are currently working. Relative paths are shorter and useful when working inside a project folder.

I used `pwd` to check my current directory. I also used `ls -l README.md` to view the detailed listing and check the file permissions.

| Permission | Meaning | Example |
|---|---|---|
| `r` — Read | It allows a user to read the contents of a file. | Opening and reading a text file. |
| `w` — Write | It allows a user to change or edit a file. | Editing a README file. |
| `x` — Execute | It allows a user to run a file as a program. For a directory, it allows access to items inside it. | Running a script. |

**Owner permissions observed:**

[Replace this line with the first three permission characters you saw in your `ls -l README.md` output. For example, `rw-` means the owner can read and write the file, but cannot execute it.]

### Task 3.4 — Operating-system responsibilities

An operating system manages the computer's hardware and provides services to applications. It helps the computer work properly and allows users to run programs.

| OS responsibility | My explanation | Example |
|---|---|---|
| Process management | The operating system manages the programs that are running. It gives them CPU time so they can work. | Running a browser and a text editor at the same time. |
| Memory management | The operating system manages the RAM used by different programs. | Giving memory to a browser when it is opened. |
| Device management | The operating system helps programs communicate with hardware devices. | Managing input from a keyboard or output to a printer. |
| File management | The operating system manages files and folders and helps us save, open, and organize them. | Saving a document inside a folder. |
| User interface / shell | It gives users a way to interact with the computer. We can use a graphical interface or a command-line shell. | Using the desktop or Terminal to give commands. |
| Security and permissions | The operating system controls access to files and other resources. | Allowing a user to edit their own file but restricting access to another user's file. |

## 3. Commands / tools used

| Command / tool | Purpose |
|---|---|
| `uname -a` | Used to view operating-system and system information. |
| `whoami` | Used to check the current user account. |
| `df -h` | Used to check used and available storage in a readable format. |
| `top -l 1` | Used to view a snapshot of system activity. |
| `ps -ax` | Used to view the list of running processes and their PIDs. |
| `pwd` | Used to display the current working directory. |
| `cd` | Used to move from one directory to another. |
| `ls -l` | Used to view files in a detailed format, including permissions. |

## 4. My understanding

After completing this mission, I understood that an operating system is an important part of a computer. It manages the hardware and helps applications run properly.

I learned that a process is a program that is running, and every process has a PID. I also learned that the operating system manages memory, storage, devices, and files.

I understood that an absolute path gives the full location of a file, while a relative path depends on the current directory. File permissions like read, write, and execute decide what actions a user can perform on a file.

These concepts are useful because they help me understand how my computer works and how to manage files and programs using Terminal.

## 5. Difficulties faced
none

## 6. Commit details
- **Commit Message**: "Documented operating system and file management"
- **Pushed to GitHub**: Yes (Verified visible on GitHub repository)