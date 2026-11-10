# MISSION 2 — Become Comfortable with the Terminal

## 1. Task

The objective of this mission was to become familiar with the command-line interface and practise basic Terminal operations.

The mission focused on:

- Inspecting directories and understanding the current working directory.
- Creating, copying, moving, renaming, and viewing files.
- Understanding the difference between replacing and appending file contents.
- Learning about command flags and pipes.
- Understanding the purpose of package managers.

## 2. Work Completed
1. Practised basic Terminal commands for navigating directories and managing files.
2. Created a practice folder named `terminal-practice`.
3. Created a text file and added two lines of text.
4. Created a backup copy and renamed the backup.
5. Practised directory listing commands with different flags.
6. Used a pipe to pass command output to another command.
7. Explored Homebrew as an example of a package manager.

### Task 2.1 — Basic Terminal Operations

| Operation | Command | What It Does | Observation |
|---|---|---|---|
| Current directory | `pwd` | Displays the full path of the current directory. | It showed the location of my working folder. |
| Directory listing | `ls` | Lists files and folders. | It displayed the contents of the current directory. |
| Detailed listing | `ls -l` | Displays detailed file and directory information. | It showed permissions, sizes, and modification dates. |
| Change directory | `cd` | Moves to another directory. | My working location changed to the selected folder. |
| Create directory | `mkdir` | Creates a new directory. | A new folder was created. |
| Create empty file | `touch` | Creates an empty file if it does not exist. | An empty text file was created. |
| Copy file | `cp` | Creates a copy of a file. | A backup copy was created while the original remained unchanged. |
| Move / rename file | `mv` | Moves or renames a file. | The backup file was renamed successfully. |
| Display file contents | `cat` | Displays the contents of a file. | The text stored in the file appeared in Terminal. |

### Task 2.2 — Practise File Changes Safely

I created a folder named `terminal-practice` inside the Mission 2 directory.

Inside this folder, I created a file named `prac.txt` and added two lines of text.

The contents of the file were:

```hello
whatsUP
```

I used the `>` operator to write the first line and the `>>` operator to append the second line.

I then created a backup using the `cp` command and renamed the backup using the `mv` command.

#### Answers to the questions

**1. What is the difference between replacing a file's contents and adding text to the end?**

Replacing a file's contents removes the existing content and writes new data. Appending adds new data to the end of the file without removing the previous content.

**2. What is the difference between copying and moving a file?**

Copying creates another version of the file while keeping the original in its location. Moving transfers the file to another location or renames it.

**3. What information does the current-directory display provide?**

The current-directory display shows the full path of the directory where Terminal is currently working.

**4. Why is a directory-listing operation useful?**

A directory listing helps users view the files and folders available in their current location. It is useful for navigating and managing files.

### Task 2.3 — Understand Flags and Pipes

I explored different directory-listing commands and compared their outputs.

| Command | Purpose |
|---|---|
| `ls` | Lists visible files and folders. |
| `ls -l` | Displays a detailed listing. |
| `ls -a` | Includes hidden files and folders. |
| `ls -lah` | Displays hidden files, detailed information, and human-readable sizes. |
| `ls -l \| head` | Displays the first few lines of a detailed directory listing. |

#### What I understood about flags

A flag is an option that modifies the behaviour of a command.

For example, the `-l` flag with `ls` displays additional information about files and folders.

The `-a` flag includes hidden files, while the `-h` flag displays file sizes in a human-readable format.

#### What I understood about pipes

The pipe symbol `|` passes the output of one command as the input of another command.

For example, in `ls -l | head`, the `ls -l` command produces a detailed directory listing, and `head` displays the first few lines.

This allows multiple commands to be combined to perform useful operations.

### Task 2.4 — Understand Package Managers

A package manager is a tool that helps users install, update, and manage software packages.

Homebrew is a package manager commonly used on macOS.

I checked the Homebrew version using:

```bash
brew --version
```

I also checked the list of packages managed by Homebrew using:

```bash
brew list
```

#### Why are package managers useful?

Package managers simplify software installation and management. They help users obtain software, update installed packages, and manage dependencies.

Homebrew is useful on macOS because it allows users to manage many development tools directly through Terminal.

## 3. Commands / Tools Used

| Command / Tool | Purpose |
|---|---|
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and directories. |
| `cd` | Changes the current directory. |
| `mkdir` | Creates a directory. |
| `touch` | Creates an empty file. |
| `cp` | Copies a file. |
| `mv` | Moves or renames a file. |
| `cat` | Displays file contents. |
| `echo` | Prints text or sends text to a file. |
| `head` | Displays the first few lines of input. |
| `brew --version` | Checks the installed Homebrew version. |
| `brew list` | Lists Homebrew-managed packages. |

## 4. My Understanding

Through this mission, I learned how to interact with my computer using Terminal instead of relying only on the graphical interface.

I understood how commands such as `pwd`, `ls`, and `cd` help me navigate directories, while commands such as `mkdir`, `touch`, `cp`, and `mv` help me manage files.

I also learned the difference between the `>` and `>>` operators. The first replaces existing file contents, while the second appends new content.

Another important concept was the use of flags and pipes. Flags modify the behaviour of commands, while pipes allow the output of one command to be passed to another command.

Finally, I understood the purpose of package managers and how Homebrew helps manage software on macOS.

## 5. Difficulties Faced
none
## 6. Evidence / Files

The following files and folders are included in this mission:

- `README.md` — Mission documentation and command reference.
- `terminal-practice/prac.txt` — Text file created during practice.
- `terminal-practice/backup.txt` — Backup copy of the text file.

Additional evidence, if included:

- `evidence/mission-02/` — Privacy-safe screenshots or selected outputs.

## 7. Commit Details
- **Commit Message**: "Complete Terminal and file management mission"
- **Pushed to GitHub**: Yes (Verified visible on GitHub repository)


