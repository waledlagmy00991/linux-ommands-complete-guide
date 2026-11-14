# 🐧 Practical Exam Linux Commands — Complete Visual Reference

A comprehensive, GitHub-formatted reference covering all **50 essential Linux commands** for the Practical Operating Systems Exam. Every command includes its literal behavior, syntax, option breakdown, real-world examples, and a **visual diagram** illustrating exactly what happens in the filesystem, terminal, or process table.

## 📑 Table of Contents

* [Category 1: Documentation & Help (`1–2`)](https://www.google.com/search?q=%23-category-1-documentation--help-12)

* [Category 2: Navigation & Directory Listing (`3–11`)](https://www.google.com/search?q=%23-category-2-navigation--directory-listing-311)

* [Category 3: Files & Directories Management (`12–22`)](https://www.google.com/search?q=%23-category-3-files--directories-management-1222)

* [Category 4: Text Viewing, Editing & Sorting (`23–29`, `50`)](https://www.google.com/search?q=%23-category-4-text-viewing-editing--sorting-2329-50)

* [Category 5: User & Group Administration (`30–42`)](https://www.google.com/search?q=%23-category-5-user--group-administration-3042)

* [Category 6: Process Monitoring & Control (`43–49`)](https://www.google.com/search?q=%23-category-6-process-monitoring--control-4349)

## 🗺️ Quick-Jump Command Index

| \# | Command | Category | One-Line Summary | 
| ----- | ----- | ----- | ----- | 
| 1 | [`man`](https://www.google.com/search?q=%231-man--manual-pages) | Help | Open full manual pages for a command | 
| 2 | [`--help`](https://www.google.com/search?q=%232---help--quick-usage-summary) | Help | Print brief usage and option flags | 
| 3 | [`ls`](https://www.google.com/search?q=%233-ls--list-directory-contents) | Navigation | List visible files and folders | 
| 4 | [`ls -a`](https://www.google.com/search?q=%234-ls--a--list-all-including-hidden) | Navigation | List all files including `.hidden` entries | 
| 5 | [`ls -l`](https://www.google.com/search?q=%235-ls--l--long-listing-format) | Navigation | List detailed permissions, owner, size, date | 
| 6 | [`ls -d`](https://www.google.com/search?q=%236-ls--d--list-directory-itself) | Navigation | List directory entry itself, not its contents | 
| 7 | [`ls -lh`](https://www.google.com/search?q=%237-ls--lh--long-listing-human-readable) | Navigation | Long format with `K`, `M`, `G` file sizes | 
| 8 | [`ls -ld`](https://www.google.com/search?q=%238-ls--ld--directory-details-in-long-format) | Navigation | Long format details of the directory itself | 
| 9 | [`ls -F`](https://www.google.com/search?q=%239-ls--f--classify-file-types) | Navigation | Append `/` for dirs, `*` for executables | 
| 10 | [`pwd`](https://www.google.com/search?q=%2310-pwd--print-working-directory) | Navigation | Show full absolute path of current location | 
| 11 | [`cd`](https://www.google.com/search?q=%2311-cd--change-directory) | Navigation | Move to another directory | 
| 12 | [`touch`](https://www.google.com/search?q=%2312-touch--create-empty-file--update-timestamp) | Files & Dirs | Create empty file or update timestamp | 
| 13 | [`mkdir`](https://www.google.com/search?q=%2313-mkdir--make-directory) | Files & Dirs | Create a new directory | 
| 14 | [`mkdir -p`](https://www.google.com/search?q=%2314-mkdir--p--make-parent-directories) | Files & Dirs | Create nested directories in one step | 
| 15 | [`cp`](https://www.google.com/search?q=%2315-cp--copy-files-or-directories) | Files & Dirs | Copy files from source to destination | 
| 16 | [`cp -i`](https://www.google.com/search?q=%2316-cp--i--interactive-copy) | Files & Dirs | Prompt before overwriting existing files | 
| 17 | [`cp -r`](https://www.google.com/search?q=%2317-cp--r--recursive-directory-copy) | Files & Dirs | Copy directories and all nested contents | 
| 18 | [`mv`](https://www.google.com/search?q=%2318-mv--move-or-rename) | Files & Dirs | Move or rename files and directories | 
| 19 | [`mv -i`](https://www.google.com/search?q=%2319-mv--i--interactive-move--rename) | Files & Dirs | Prompt before overwriting on move/rename | 
| 20 | [`rm`](https://www.google.com/search?q=%2320-rm--remove-files) | Files & Dirs | Permanently delete files | 
| 21 | [`rm -r`](https://www.google.com/search?q=%2321-rm--r--recursive-remove) | Files & Dirs | Recursively delete directories and contents | 
| 22 | [`rmdir`](https://www.google.com/search?q=%2322-rmdir--remove-empty-directory) | Files & Dirs | Delete a directory only if it is empty | 
| 23 | [`echo`](https://www.google.com/search?q=%2323-echo--display-text-or-variables) | Text | Print text/variables or redirect to a file | 
| 24 | [`cat`](https://www.google.com/search?q=%2324-cat--concatenate--display-files) | Text | Print and combine file contents to stdout | 
| 25 | [`nano`](https://www.google.com/search?q=%2325-nano--beginner-friendly-text-editor) | Text | Simple terminal text editor | 
| 26 | [`head`](https://www.google.com/search?q=%2326-head--display-beginning-of-file) | Text | Print first 10 lines (default) of a file | 
| 27 | [`tail`](https://www.google.com/search?q=%2327-tail--display-end-of-file) | Text | Print last 10 lines (default) of a file | 
| 28 | [`grep`](https://www.google.com/search?q=%2328-grep--search-text-patterns) | Text | Search for matching text patterns | 
| 29 | [`vi`](https://www.google.com/search?q=%2329-vi--traditional-modal-text-editor) | Text | Powerful modal text editor (`vi`/`vim`) | 
| 30 | [`useradd`](https://www.google.com/search?q=%2330-useradd--create-new-user-account) | Users | Create a new user account | 
| 31 | [`useradd -d`](https://www.google.com/search?q=%2331-useradd--d--create-user-with-custom-home) | Users | Create user with custom home directory | 
| 32 | [`useradd -u`](https://www.google.com/search?q=%2332-useradd--u--create-user-with-custom-uid) | Users | Create user with specific User ID (UID) | 
| 33 | [`usermod`](https://www.google.com/search?q=%2333-usermod--modify-existing-user) | Users | Modify properties of an existing user | 
| 34 | [`usermod -d`](https://www.google.com/search?q=%2334-usermod--d--change-users-home-directory) | Users | Change an existing user's home directory | 
| 35 | [`usermod -u`](https://www.google.com/search?q=%2335-usermod--u--change-users-uid) | Users | Change an existing user's UID | 
| 36 | [`usermod -p`](https://www.google.com/search?q=%2336-usermod--p--set-encrypted-password) | Users | Set an encrypted password for a user | 
| 37 | [`userdel`](https://www.google.com/search?q=%2337-userdel--delete-user-account) | Users | Delete an existing user account | 
| 38 | [`groupadd`](https://www.google.com/search?q=%2338-groupadd--create-new-group) | Groups | Create a new user group | 
| 39 | [`groupadd -g`](https://www.google.com/search?q=%2339-groupadd--g--create-group-with-custom-gid) | Groups | Create a group with specific Group ID (GID) | 
| 40 | [`groupadd -p`](https://www.google.com/search?q=%2340-groupadd--p--create-group-with-password) | Groups | Set an encrypted password for a new group | 
| 41 | [`groupmod`](https://www.google.com/search?q=%2341-groupmod--modify-existing-group) | Groups | Modify an existing group's name or GID | 
| 42 | [`groupdel`](https://www.google.com/search?q=%2342-groupdel--delete-group) | Groups | Delete an existing group | 
| 43 | [`ps`](https://www.google.com/search?q=%2343-ps--process-status-snapshot) | Processes | Snapshot of current shell processes | 
| 44 | [`ps aux`](https://www.google.com/search?q=%2344-ps-aux--all-processes-user-oriented) | Processes | All system processes in user-oriented format | 
| 45 | [`ps -e`](https://www.google.com/search?q=%2345-ps--e--every-running-process) | Processes | Every running process on the system | 
| 46 | [`top`](https://www.google.com/search?q=%2346-top--real-time-process-monitor) | Processes | Live dynamic view of CPU, RAM, and processes | 
| 47 | [`kill`](https://www.google.com/search?q=%2347-kill--send-signal-to-process-by-pid) | Processes | Send a signal (e.g., terminate) by PID | 
| 48 | [`killall`](https://www.google.com/search?q=%2348-killall--send-signal-to-processes-by-name) | Processes | Signal all processes matching a name | 
| 49 | [`pgrep`](https://www.google.com/search?q=%2349-pgrep--find-pids-by-process-name) | Processes | Search processes by name and return PIDs | 
| 50 | [`sort`](https://www.google.com/search?q=%2350-sort--sort-lines-of-text) | Text | Sort lines alphabetically or numerically | 

## 📖 Category 1: Documentation & Help (`1–2`)

### 1. `man` — Manual Pages

Opens the built-in, comprehensive reference manual for any Linux command, system call, or configuration file. It displays sections such as `NAME`, `SYNOPSIS`, `DESCRIPTION`, `OPTIONS`, and `EXAMPLES` inside a scrollable pager (`less`).

* **Syntax:** `man [section] <command>`

* **Example:**

  ```
  man ls
  
  ```

* **Visual Result:**

  ```
  ┌──────────────────────────────────────────────────────┐
  │ 📖 LS(1)              User Commands            LS(1) │
  ├──────────────────────────────────────────────────────┤
  │ NAME                                                 │
  │      ls - list directory contents                    │
  │ SYNOPSIS                                             │
  │      ls [OPTION]... [FILE]...                        │
  │ DESCRIPTION                                          │
  │      List information about the FILEs...             │
  └──────────────────────────────────────────────────────┘
  Navigation: [Space] Next Page  |  [/word] Search  |  [q] Quit
  
  ```

> \[!TIP\]
> Press `q` at any time to exit the manual page, or press `/` followed by a keyword (e.g., `/recursive`) and `Enter` to search inside the manual.

### 2. `--help` — Quick Usage Summary

A standard option supported by almost all GNU/Linux utilities that prints a concise summary of syntax, available flags, and brief descriptions directly to the terminal without opening a separate pager.

* **Syntax:** `<command> --help`

* **Example:**

  ```
  mkdir --help
  
  ```

* **Visual Result:**

  ```
  Terminal Output (stdout)
  └── 📋 Usage: mkdir [OPTION]... DIRECTORY...
      ├── -m, --mode=MODE   set file mode (as in chmod)
      ├── -p, --parents     no error if existing, make parent directories
      └── -v, --verbose     print a message for each created directory
  
  ```

## 🧭 Category 2: Navigation & Directory Listing (`3–11`)

### 3. `ls` — List Directory Contents

Lists the **visible** files and subdirectories inside the current working directory (or a specified target path), sorted alphabetically.

* **Syntax:** `ls [directory_path]`

* **Example:**

  ```
  ls
  
  ```

* **Visual Result:**

  ```
  📂 Current Directory
  ├── 📄 notes.txt
  ├── 📄 report.pdf
  └── 📁 projects/
  
  ```

  *Output:* `notes.txt   projects   report.pdf`

### 4. `ls -a` — List All (Including Hidden)

Lists **all** entries in a directory, including **hidden files and directories** whose names begin with a dot (`.`), as well as the special entries `.` (current directory) and `..` (parent directory).

* **Syntax:** `ls -a [directory_path]`

* **Example:**

  ```
  ls -a
  
  ```

* **Visual Result:**

  ```
  📂 Current Directory (with -a)
  ├── 📁 .           (current directory pointer)
  ├── 📁 ..          (parent directory pointer)
  ├── 🔒 .bashrc     (hidden config file)
  ├── 🔒 .env        (hidden environment file)
  ├── 📄 notes.txt
  └── 📁 projects/
  
  ```

### 5. `ls -l` — Long Listing Format

Displays detailed metadata for each file and directory in a structured table: file type, permissions, hard link count, owner, group, size in bytes, last modification timestamp, and name.

* **Syntax:** `ls -l [path]`

* **Example:**

  ```
  ls -l
  
  ```

* **Visual Result:**

  ```
  -rw-r--r--  1  waleed  students  2048  Nov 15 01:30  notes.txt
  │└───────┘  │    │       │        │         │           │
  │    │      │    │       │        │         │           └── 📄 File Name
  │    │      │    │       │        │         └────────────── 🕒 Last Modified
  │    │      │    │       │        └──────────────────────── 📏 Size (Bytes)
  │    │      │    │       └───────────────────────────────── 👥 Group Owner
  │    │      │    └───────────────────────────────────────── 👤 User Owner
  │    │      └────────────────────────────────────────────── 🔗 Link Count
  │    └───────────────────────────────────────────────────── 🔐 Permissions (u/g/o)
  └────────────────────────────────────────────────────────── 📌 Type (- file, d dir)
  
  ```

### 6. `ls -d` — List Directory Itself

Tells `ls` to treat a directory argument as a single entry and **display the directory itself** rather than listing the files inside it. Most commonly combined with `-l` (`ls -ld`).

* **Syntax:** `ls -d <directory_name>`

* **Example:**

  ```
  ls -d projects/
  
  ```

* **Visual Result:**

  ```
  ls projects/     ──▶ Lists contents INSIDE: 📄 app.py, 📄 README.md
  ls -d projects/  ──▶ Lists ONLY the folder itself: 📁 projects/
  
  ```

### 7. `ls -lh` — Long Listing (Human-Readable)

Combines `-l` (long format) with `-h` (human-readable) so file sizes are automatically converted from raw bytes into readable units like `K` (Kilobytes), `M` (Megabytes), and `G` (Gigabytes).

* **Syntax:** `ls -lh [path]`

* **Example:**

  ```
  ls -lh
  
  ```

* **Visual Result:**

  ```
  Before (-l):   -rw-r--r-- 1 waleed users  15728640 Nov 15 01:30 dataset.csv
  After  (-lh):  -rw-r--r-- 1 waleed users       15M Nov 15 01:30 dataset.csv
                                                ▲
                                   📊 15,728,640 B ──▶ 15M
  
  ```

### 8. `ls -ld` — Directory Details in Long Format

Combines `-l` and `-d` to inspect the **permissions, ownership, and timestamp of a directory itself**, rather than the items stored inside it.

* **Syntax:** `ls -ld <directory_name>`

* **Example:**

  ```
  ls -ld /home/waleed
  
  ```

* **Visual Result:**

  ```
  drwxr-xr-x 5 waleed waleed 4096 Nov 15 01:00 /home/waleed
  ▲                                               │
  └── 📁 Permissions & metadata of THIS folder ───┘
  
  ```

### 9. `ls -F` — Classify File Types

Appends a single trailing symbol to each entry name so you can identify file types at a glance without reading long permissions.

* **Syntax:** `ls -F [path]`

* **Example:**

  ```
  ls -F
  
  ```

* **Visual Result:**

  ```
  📂 Current Directory (with -F)
  ├── 📁 projects/     ──▶ "/"  Directory
  ├── ⚙️ run.sh*       ──▶ "*"  Executable file
  ├── 🔗 latest@       ──▶ "@"  Symbolic link
  └── 📄 notes.txt     ──▶ (no symbol) Regular file
  
  ```

### 10. `pwd` — Print Working Directory

Prints the **full absolute path** of your current location in the Linux filesystem hierarchy, starting from the root directory `/`.

* **Syntax:** `pwd`

* **Example:**

  ```
  pwd
  
  ```

* **Visual Result:**

  ```
  / (root)
   └── home
        └── waleed
             └── os_exam  ◀── 📍 You are here: /home/waleed/os_exam
  
  ```

### 11. `cd` — Change Directory

Moves your shell session from the current working directory to another directory.

* **Syntax:** `cd [target_directory]`

* **Quick Shortcuts:**

| Command | Destination | 
| ----- | ----- | 
| `cd /etc` | Jump to absolute path `/etc` | 
| `cd projects` | Enter relative subfolder `projects` | 
| `cd ..` | Move **up** one level to parent directory | 
| `cd ~` or `cd` | Return to your **home** directory | 
| `cd -` | Switch back to the **previous** directory | 

* **Visual Result:**

  ```
  📍 /home/waleed/os_exam
       │
       ├── cd ..        ──▶ 📍 /home/waleed
       ├── cd projects  ──▶ 📍 /home/waleed/os_exam/projects
       └── cd ~         ──▶ 📍 /home/waleed
  
  ```

## 📂 Category 3: Files & Directories Management (`12–22`)

### 12. `touch` — Create Empty File / Update Timestamp

If the file **does not exist**, `touch` creates a brand-new **0-byte empty file**. If the file **already exists**, it updates its last-accessed and last-modified timestamps without altering its contents.

* **Syntax:** `touch <file1> [file2 ...]`

* **Example:**

  ```
  touch exam_notes.txt
  
  ```

* **Visual Result:**

  ```
  Before:  📂 os_exam/ (empty)
  After:   📂 os_exam/
           └── 📄 exam_notes.txt  (0 bytes, created now)
  
  ```

### 13. `mkdir` — Make Directory

Creates a new, empty directory inside the current location (or at a specified existing parent path).

* **Syntax:** `mkdir <directory_name>`

* **Example:**

  ```
  mkdir lab_work
  
  ```

* **Visual Result:**

  ```
  Before:  📂 os_exam/
  After:   📂 os_exam/
           └── 📁 lab_work/  (new empty folder)
  
  ```

### 14. `mkdir -p` — Make Parent Directories

Creates an entire nested directory hierarchy in a single command. If any parent folders in the path do not exist yet, `-p` creates them automatically without throwing an error (and does not fail if the folder already exists).

* **Syntax:** `mkdir -p <parent/child/grandchild>`

* **Example:**

  ```
  mkdir -p semester_3/os_course/practical_exam
  
  ```

* **Visual Result:**

  ```
  📁 semester_3/              ◀── Created automatically
  └── 📁 os_course/           ◀── Created automatically
      └── 📁 practical_exam/  ◀── Target folder created
  
  ```

### 15. `cp` — Copy Files or Directories

Duplicates a file from a source path to a destination path, leaving the original file untouched.

* **Syntax:** `cp <source_file> <destination>`

* **Example:**

  ```
  cp exam_notes.txt exam_backup.txt
  
  ```

* **Visual Result:**

  ```
  Before:  📄 exam_notes.txt
  After:   📄 exam_notes.txt   (original)
           📄 exam_backup.txt  (exact duplicate 📋)
  
  ```

### 16. `cp -i` — Interactive Copy

Safely copies files by **prompting for confirmation (`y/n`)** before overwriting an existing file at the destination.

* **Syntax:** `cp -i <source_file> <destination_file>`

* **Example:**

  ```
  cp -i exam_notes.txt exam_backup.txt
  
  ```

* **Visual Result:**

  ```
  ⚠️  cp: overwrite 'exam_backup.txt'? _
      ├── Type 'y' + Enter ──▶ Overwrites destination 📄
      └── Type 'n' + Enter ──▶ Cancels safely 🛡️
  
  ```

### 17. `cp -r` — Recursive Directory Copy

Copies a directory **recursively**, meaning it duplicates the folder itself along with every file and subdirectory nested inside it.

* **Syntax:** `cp -r <source_dir> <destination_dir>`

* **Example:**

  ```
  cp -r lab_work lab_work_backup
  
  ```

* **Visual Result:**

  ```
  📁 lab_work/                     📁 lab_work_backup/ (copied)
  ├── 📄 script.sh       ═══▶      ├── 📄 script.sh
  └── 📁 data/                     └── 📁 data/
      └── 📄 log.txt                   └── 📄 log.txt
  
  ```

### 18. `mv` — Move or Rename

Performs two operations depending on the destination:

1. **Moves** a file or directory to a different folder.

2. **Renames** a file or directory when the destination is a new name in the same folder.

* **Syntax:** `mv <source> <destination>`

* **Example:**

  ```
  mv exam_notes.txt final_notes.txt      # Rename
  mv final_notes.txt lab_work/           # Move into folder
  
  ```

* **Visual Result:**

  ```
  Rename:  📄 exam_notes.txt  ──▶  📄 final_notes.txt
  Move:    📄 final_notes.txt ──▶  📁 lab_work/
                                   └── 📄 final_notes.txt
  
  ```

### 19. `mv -i` — Interactive Move / Rename

Moves or renames files safely by **asking for confirmation** if a file with the same name already exists at the destination.

* **Syntax:** `mv -i <source> <destination>`

* **Example:**

  ```
  mv -i draft.txt final_notes.txt
  
  ```

* **Visual Result:**

  ```
  ⚠️  mv: overwrite 'final_notes.txt'? _
      ├── 'y' ──▶ Replaces destination
      └── 'n' ──▶ Keeps both files untouched 🛡️
  
  ```

### 20. `rm` — Remove Files

Permanently deletes one or more files from the filesystem.

* **Syntax:** `rm <file1> [file2 ...]`

* **Example:**

  ```
  rm exam_backup.txt
  
  ```

* **Visual Result:**

  ```
  Before:  📂 os_exam/ ──▶ 📄 exam_backup.txt
  After:   📂 os_exam/ ──▶ 🗑️ (permanently deleted)
  
  ```

> \[!CAUTION\]
> Linux `rm` does **not** move files to a Trash/Recycle Bin. Once deleted with `rm`, files cannot be easily recovered.

### 21. `rm -r` — Recursive Remove

Recursively deletes a directory and **everything inside it** (all files and nested subdirectories).

* **Syntax:** `rm -r <directory_name>`

* **Example:**

  ```
  rm -r lab_work_backup
  
  ```

* **Visual Result:**

  ```
  📁 lab_work_backup/
  ├── 📄 script.sh     ──▶ 🗑️ Deleted
  └── 📁 data/         ──▶ 🗑️ Deleted
      └── 📄 log.txt   ──▶ 🗑️ Deleted
  
  ```

> \[!WARNING\]
> Double-check your path before running `rm -r`. Never run `rm -rf /` or `rm -rf *` blindly.

### 22. `rmdir` — Remove Empty Directory

Deletes a directory **only if it is completely empty**. If the directory contains any files or hidden dotfiles, `rmdir` refuses to delete it and returns an error.

* **Syntax:** `rmdir <empty_directory>`

* **Example:**

  ```
  rmdir empty_folder
  
  ```

* **Visual Result:**

  ```
  📁 empty_folder/ (0 items)   ──▶ 🗑️ Removed successfully
  📁 full_folder/  (has files) ──▶ ❌ Error: Directory not empty
  
  ```

## 📝 Category 4: Text Viewing, Editing & Sorting (`23–29`, `50`)

### 23. `echo` — Display Text or Variables

Prints a line of text or the value of an environment variable (like `$USER` or `$PATH`) to standard output (`stdout`). Often combined with `>` (overwrite) or `>>` (append) to write text into files.

* **Syntax:** `echo [text_or_$VARIABLE]`

* **Example:**

  ```
  echo "Hello Linux Exam!" > welcome.txt
  echo $USER
  
  ```

* **Visual Result:**

  ```
  echo "Hello Linux Exam!" ──▶ 🖥️ Terminal: Hello Linux Exam!
  echo "Hello" > file.txt  ──▶ 📄 file.txt (writes/overwrites content)
  echo "World" >> file.txt ──▶ 📄 file.txt (appends to end of file)
  
  ```

### 24. `cat` — Concatenate & Display Files

Reads one or more files sequentially and prints their entire content to the terminal (`stdout`). Can also merge multiple files into a single file using `>`.

* **Syntax:** `cat <file1> [file2 ...]`

* **Example:**

  ```
  cat welcome.txt
  cat part1.txt part2.txt > combined.txt
  
  ```

* **Visual Result:**

  ```
  📄 part1.txt ──┐
                 ├──▶ [ cat ] ──▶ 🖥️ Combined Output / 📄 combined.txt
  📄 part2.txt ──┘
  
  ```

### 25. `nano` — Beginner-Friendly Text Editor

A lightweight, intuitive command-line text editor that displays keyboard shortcuts directly at the bottom of the terminal window (`^` stands for `Ctrl`).

* **Syntax:** `nano <filename>`

* **Example:**

  ```
  nano script.sh
  
  ```

* **Visual Result:**

  ```
  ┌──────────────────────────────────────────────┐
  │   GNU nano 7.2         script.sh             │
  │ #!/bin/bash                                  │
  │ echo "Studying for OS Practical Exam"        │
  │                                              │
  │ ^O Write Out (Save)    ^X Exit               │
  │ ^K Cut Line            ^U Paste Line         │
  └──────────────────────────────────────────────┘
  
  ```

### 26. `head` — Display Beginning of File

Outputs the **first 10 lines** of a file by default. Use `-n <count>` to specify a custom number of lines.

* **Syntax:** `head [-n N] <filename>`

* **Example:**

  ```
  head -n 5 server.log
  
  ```

* **Visual Result:**

  ```
  📄 server.log (100 lines)
  ├── Line 1   ◀── 🟢 Printed
  ├── Line 2   ◀── 🟢 Printed
  ├── ...
  ├── Line 5   ◀── 🟢 Printed
  └── Lines 6–100  (ignored)
  
  ```

### 27. `tail` — Display End of File

Outputs the **last 10 lines** of a file by default. Ideal for checking the most recent log entries; `-n <count>` controls how many lines are shown, and `-f` follows live updates.

* **Syntax:** `tail [-n N] <filename>`

* **Example:**

  ```
  tail -n 5 server.log
  
  ```

* **Visual Result:**

  ```
  📄 server.log (100 lines)
  ├── Lines 1–95   (ignored)
  ├── Line 96  ◀── 🟢 Printed
  ├── ...
  └── Line 100 ◀── 🟢 Printed
  
  ```

### 28. `grep` — Search Text Patterns

Searches line-by-line for a specified text string or regular expression inside a file or piped input stream, printing every matching line.

* **Syntax:** `grep [options] "pattern" <filename>`

* **Useful Flags:** `-i` (case-insensitive), `-n` (show line numbers), `-v` (invert match).

* **Example:**

  ```
  grep -in "error" server.log
  
  ```

* **Visual Result:**

  ```
  📄 server.log
  ├── Line 1: INFO Started
  ├── Line 2: ERROR Disk full   ──▶ 🔍 Match! ──▶ 2:ERROR Disk full
  └── Line 3: INFO Running
  
  ```

### 29. `vi` — Traditional Modal Text Editor

A classic, high-efficiency modal text editor installed on virtually every Unix/Linux system (often aliased or upgraded to `vim`). Unlike `nano`, `vi` separates navigation from typing using **modes**.

* **Syntax:** `vi <filename>`

* **Example:**

  ```
  vi config.txt
  
  ```

* **Visual Mode Flow:**

  ```
  [ Normal Mode ] ──( press 'i' or 'a' )──▶ [ Insert Mode ] (type text)
         ▲                                         │
         └────────────( press 'Esc' )──────────────┘
         │
         └──( type ':' )──▶ [ Command Mode ]
                            ├── :w   (Save)
                            ├── :q   (Quit)
                            ├── :wq  (Save & Quit)
                            └── :q!  (Force Quit without saving)
  
  ```

### 50. `sort` — Sort Lines of Text

Reads lines from a text file or standard input and prints them sorted alphabetically (A–Z) by default. Useful flags include `-r` (reverse) and `-n` (numeric sort).

* **Syntax:** `sort [options] <filename>`

* **Example:**

  ```
  sort names.txt
  sort -nr scores.txt   # Numeric reverse (highest first)
  
  ```

* **Visual Result:**

  ```
  📄 names.txt (Before)       🖥️ Output (After sort)
  ├── Zain                    ├── Ali
  ├── Ali              ──▶    ├── Omar
  └── Omar                    └── Zain
  
  ```

## 👥 Category 5: User & Group Administration (`30–42`)

> \[!IMPORTANT\]
> User and group management commands modify system files (`/etc/passwd`, `/etc/shadow`, `/etc/group`) and require **root privileges** (`sudo`).

### 30. `useradd` — Create New User Account

Creates a new user account on the system and registers its entry in `/etc/passwd`.

* **Syntax:** `sudo useradd <username>`

* **Example:**

  ```
  sudo useradd ahmed
  
  ```

* **Visual Result:**

  ```
  👤 New User Created: ahmed
  └── 📄 /etc/passwd updated: ahmed:x:1001:1001::/home/ahmed:/bin/sh
  
  ```

### 31. `useradd -d` — Create User with Custom Home

Creates a new user account while explicitly specifying the path to their **home directory** (often paired with `-m` to create the directory if it doesn't exist).

* **Syntax:** `sudo useradd -m -d <custom_home_path> <username>`

* **Example:**

  ```
  sudo useradd -m -d /home/students/sara sara
  
  ```

* **Visual Result:**

  ```
  👤 User: sara
  └── 🏠 Home Folder: 📁 /home/students/sara/ (custom path)
  
  ```

### 32. `useradd -u` — Create User with Custom UID

Creates a new user account with a specific numeric **User ID (UID)** instead of letting the system auto-assign the next available UID.

* **Syntax:** `sudo useradd -u <UID> <username>`

* **Example:**

  ```
  sudo useradd -u 2050 omar
  
  ```

* **Visual Result:**

  ```
  👤 User: omar
  └── 🪪 UID: 2050  (recorded in /etc/passwd)
  
  ```

### 33. `usermod` — Modify Existing User

Modifies settings of an **already existing** user account (such as login name `-l`, shell `-s`, or supplementary groups `-aG`).

* **Syntax:** `sudo usermod [options] <username>`

* **Example:**

  ```
  sudo usermod -s /bin/bash ahmed
  
  ```

* **Visual Result:**

  ```
  👤 User: ahmed
  └── ⚙️ Login Shell updated: /bin/sh ──▶ /bin/bash
  
  ```

### 34. `usermod -d` — Change User's Home Directory

Updates an existing user's home directory path in `/etc/passwd` (combine with `-m` to physically move the old home contents to the new location).

* **Syntax:** `sudo usermod -d <new_home_path> [-m] <username>`

* **Example:**

  ```
  sudo usermod -d /home/grad_ahmed -m ahmed
  
  ```

* **Visual Result:**

  ```
  👤 User: ahmed
  ├── Old Home: 📁 /home/ahmed
  └── New Home: 📁 /home/grad_ahmed (updated & moved)
  
  ```

### 35. `usermod -u` — Change User's UID

Changes the numeric **User ID (UID)** of an existing user account.

* **Syntax:** `sudo usermod -u <new_UID> <username>`

* **Example:**

  ```
  sudo usermod -u 3005 ahmed
  
  ```

* **Visual Result:**

  ```
  👤 User: ahmed
  └── 🪪 UID: 1001 ──▶ 3005
  
  ```

### 36. `usermod -p` — Set Encrypted Password

Updates an existing user's password in `/etc/shadow`. **Crucial:** `-p` expects an **already encrypted password hash** (not plain text), typically generated with `openssl passwd -6`.

* **Syntax:** `sudo usermod -p '<encrypted_hash>' <username>`

* **Example:**

  ```
  sudo usermod -p "$(openssl passwd -6 MySecretPass)" ahmed
  
  ```

* **Visual Result:**

  ```
  🔑 Plain Text ──▶ [openssl passwd -6] ──▶ 🔒 $6$salt$hash... ──▶ 📄 /etc/shadow
  
  ```

> \[!WARNING\]
> Passing plain text directly to `usermod -p` stores it unencrypted and prevents login. For interactive password changes, `passwd <username>` is used instead.

### 37. `userdel` — Delete User Account

Removes a user account from the system (`/etc/passwd`, `/etc/shadow`). Add `-r` (`userdel -r`) if you also want to delete their home directory and mail spool.

* **Syntax:** `sudo userdel [-r] <username>`

* **Example:**

  ```
  sudo userdel -r ahmed
  
  ```

* **Visual Result:**

  ```
  👤 ahmed ──▶ ❌ Removed from /etc/passwd
  📁 /home/ahmed ──▶ 🗑️ Removed (when using -r)
  
  ```

### 38. `groupadd` — Create New Group

Creates a new user group and registers it in `/etc/group`.

* **Syntax:** `sudo groupadd <groupname>`

* **Example:**

  ```
  sudo groupadd developers
  
  ```

* **Visual Result:**

  ```
  👥 New Group Created: developers
  └── 📄 /etc/group updated: developers:x:1002:
  
  ```

### 39. `groupadd -g` — Create Group with Custom GID

Creates a new group with a specific numeric **Group ID (GID)**.

* **Syntax:** `sudo groupadd -g <GID> <groupname>`

* **Example:**

  ```
  sudo groupadd -g 5000 cs_students
  
  ```

* **Visual Result:**

  ```
  👥 Group: cs_students
  └── 🪪 GID: 5000
  
  ```

### 40. `groupadd -p` — Create Group with Password

Sets an **encrypted password** for a newly created group (stored in `/etc/gshadow`).

* **Syntax:** `sudo groupadd -p '<encrypted_hash>' <groupname>`

* **Example:**

  ```
  sudo groupadd -p "$(openssl passwd -6 GroupPass)" secret_team
  
  ```

* **Visual Result:**

  ```
  👥 Group: secret_team ──▶ 🔒 Protected with encrypted hash in /etc/gshadow
  
  ```

### 41. `groupmod` — Modify Existing Group

Modifies an existing group's name (`-n`) or numeric GID (`-g`).

* **Syntax:** `sudo groupmod [-n new_name] [-g new_GID] <groupname>`

* **Example:**

  ```
  sudo groupmod -n dev_team developers
  
  ```

* **Visual Result:**

  ```
  👥 Group Renamed: developers ──▶ dev_team
  
  ```

### 42. `groupdel` — Delete Group

Deletes an existing group from `/etc/group` (cannot delete a user's primary group while the user still exists).

* **Syntax:** `sudo groupdel <groupname>`

* **Example:**

  ```
  sudo groupdel dev_team
  
  ```

* **Visual Result:**

  ```
  👥 dev_team ──▶ ❌ Removed from /etc/group
  
  ```

## ⚙️ Category 6: Process Monitoring & Control (`43–49`)

### 43. `ps` — Process Status Snapshot

Displays a static snapshot of processes running **in your current terminal session** only.

* **Syntax:** `ps`

* **Example:**

  ```
  ps
  
  ```

* **Visual Result:**

  ```
    PID TTY          TIME CMD
   1042 pts/0    00:00:00 bash
   1185 pts/0    00:00:00 ps
   ▲    ▲                 ▲
   │    │                 └── ⚙️ Command name
   │    └──────────────────── 🖥️ Current terminal
   └───────────────────────── 🪪 Process ID
  
  ```

### 44. `ps aux` — All Processes (User-Oriented)

Shows **every process** on the system in a detailed, user-friendly format:

* `a`: processes for all users

* `u`: display user/owner, `%CPU`, and `%MEM` columns

* `x`: include background daemons without a controlling terminal

* **Syntax:** `ps aux`

* **Example:**

  ```
  ps aux | head -n 5
  
  ```

* **Visual Result:**

  ```
  USER       PID %CPU %MEM    VSZ   RSS TTY  STAT START   TIME COMMAND
  root         1  0.0  0.1 168936 11840 ?    Ss   01:00   0:02 /sbin/init
  waleed    1042  0.1  0.2  10240  5120 pts0 Ss   01:10   0:00 -bash
  
  ```

### 45. `ps -e` — Every Running Process

Uses standard UNIX syntax to list **every active process** across the entire system (equivalent to `ps -A`).

* **Syntax:** `ps -e`

* **Example:**

  ```
  ps -e | head -n 5
  
  ```

* **Visual Result:**

  ```
  🖥️ Entire System Process Table
  ├── PID 1     systemd
  ├── PID 420   sshd
  └── PID 1042  bash
  
  ```

### 46. `top` — Real-Time Process Monitor

Launches an interactive, **live-updating dashboard** showing CPU load, memory/swap usage, uptime, and the most resource-hungry processes sorted in real time.

* **Syntax:** `top` (or `top -b -n 1` for a non-interactive snapshot)

* **Example:**

  ```
  top
  
  ```

* **Visual Result:**

  ```
  ┌───────────────────────────────────────────────────────────┐
  │ top - 01:40:12 up 2:15,  1 user,  load average: 0.12      │
  │ %Cpu(s):  4.2 us,  1.1 sy,  0.0 ni, 94.5 id               │
  │ MiB Mem :  16000 total,   8400 free,   4200 used          │
  ├───────────────────────────────────────────────────────────┤
  │   PID USER      %CPU %MEM  COMMAND                        │
  │  2310 waleed    12.4  3.1  python3                        │
  │  1042 waleed     0.3  0.1  bash                           │
  └───────────────────────────────────────────────────────────┘
  Keys: [q] Quit  |  [M] Sort by Memory  |  [P] Sort by CPU  |  [k] Kill PID
  
  ```

### 47. `kill` — Send Signal to Process by PID

Sends a specific signal to a running process identified by its **PID**. By default, it sends `SIGTERM` (`-15`) to request a graceful shutdown; `-9` (`SIGKILL`) forces immediate termination.

* **Syntax:** `kill [-SIGNAL] <PID>`

* **Example:**

  ```
  kill 2310       # Graceful termination (SIGTERM -15)
  kill -9 2310    # Force kill (SIGKILL -9)
  
  ```

* **Visual Result:**

  ```
  kill -15 2310 ──▶ 📨 SIGTERM ──▶ ⚙️ Process 2310 ──▶ 🛑 Clean Shutdown
  kill -9  2310 ──▶ ⚡ SIGKILL ──▶ ⚙️ Process 2310 ──▶ 💥 Force Terminated
  
  ```

### 48. `killall` — Send Signal to Processes by Name

Sends a signal to **all running processes whose command name matches** the specified name, saving you from looking up multiple PIDs.

* **Syntax:** `killall [-SIGNAL] <process_name>`

* **Example:**

  ```
  killall sleep
  
  ```

* **Visual Result:**

  ```
  ⚙️ sleep (PID 301) ◀──┐
  ⚙️ sleep (PID 302) ◀──┼── [ killall sleep ] ──▶ 🛑 All terminated
  ⚙️ sleep (PID 303) ◀──┘
  
  ```

### 49. `pgrep` — Find PIDs by Process Name

Searches currently running processes by name (or attributes like user `-u`) and outputs **only their matching PIDs**—making it cleaner than `ps aux | grep`.

* **Syntax:** `pgrep [options] <pattern>`

* **Example:**

  ```
  pgrep -l python3   # -l also prints the process name next to PID
  
  ```

* **Visual Result:**

  ```
  🔍 Search: "python3"
  └── 🖥️ Output:
      2310 python3
      2455 python3
  
  ```

<div align="center">

**Made for the Operating Systems Practical Exam** · 🐧 *Good luck!*

</div>