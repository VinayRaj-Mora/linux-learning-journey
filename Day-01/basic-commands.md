# Linux File Management Commands

## Navigation Commands

- `pwd` → Displays the current working directory.
- `ls` → Lists files and directories.
- `ls -l` → Lists files and directories in long (detailed) format.
- `ls -a` → Lists all files, including hidden files.
- `ls -la` → Lists all files with detailed information.
- `cd <directory>` → Changes the current directory.
- `cd ..` → Moves to the parent directory.
- `cd ~` → Moves to the current user's home directory.
- `cd /` → Moves to the root directory.
- `cd -` → Switches to the previous working directory.
- `tree` → Displays directories and files in a tree structure.

---

# File Creation Commands

- `touch <file>` → Creates an empty file.
- `mkdir <directory>` → Creates a new directory.
- `mkdir -p <path>` → Creates nested directories if they don't exist.

---

# File Viewing Commands

- `cat <file>` → Displays the entire contents of a file.
- `less <file>` → Opens a file for page-by-page viewing (forward and backward).
- `more <file>` → Displays a file one page at a time.
- `head <file>` → Displays the first 10 lines of a file.
- `head -n <number> <file>` → Displays the first specified number of lines.
- `tail <file>` → Displays the last 10 lines of a file.
- `tail -n <number> <file>` → Displays the last specified number of lines.
- `tail -f <file>` → Monitors a file in real time as new content is added.

---

# File Copy and Move Commands

- `cp <source> <destination>` → Copies a file.
- `cp -r <source> <destination>` → Copies a directory and its contents.
- `mv <source> <destination>` → Moves or renames a file or directory.

---

# File Deletion Commands

- `rm <file>` → Deletes a file.
- `rm -r <directory>` → Deletes a directory and its contents.
- `rm -rf <directory>` → Forcefully deletes a directory and all its contents.
- `rmdir <directory>` → Deletes an empty directory.

---

# Search Commands

- `find <path> -name <filename>` → Searches for a file or directory.
- `locate <filename>` → Quickly finds files using the system database.
- `which <command>` → Displays the location of a command.
- `whereis <command>` → Displays the binary, source, and manual page locations of a command.

---

# File Information Commands

- `file <file>` → Displays the type of a file.
- `stat <file>` → Displays detailed information about a file.
- `realpath <file>` → Displays the absolute path of a file or directory.

---

# Disk Usage Commands

- `du -sh <directory>` → Displays the size of a directory.
- `df -h` → Displays disk space usage of all mounted file systems.
- `lsblk` → Lists all storage devices and partitions.

---

# Mount Commands

- `mount` → Displays mounted file systems or mounts a device.
- `umount <mount_point>` → Unmounts a mounted file system.

---

# File Permission Commands

- `chmod <permissions> <file>` → Changes file or directory permissions.
- `chown <user>:<group> <file>` → Changes the owner and group of a file.
- `chgrp <group> <file>` → Changes the group ownership of a file.

---

# File Compression Commands

- `tar -cvf archive.tar <directory>` → Creates a tar archive.
- `tar -xvf archive.tar` → Extracts a tar archive.
- `gzip <file>` → Compresses a file.
- `gunzip <file.gz>` → Decompresses a gzip file.
- `zip archive.zip <file>` → Creates a ZIP archive.
- `unzip archive.zip` → Extracts a ZIP archive.

---

# File Comparison Commands

- `diff <file1> <file2>` → Compares two files line by line.
- `cmp <file1> <file2>` → Compares two files byte by byte.

---

# Link Commands

- `ln <source> <link>` → Creates a hard link.
- `ln -s <source> <link>` → Creates a symbolic (soft) link.

---

# Useful Shortcuts

- `history` → Displays previously executed commands.
- `clear` → Clears the terminal screen.
- `man <command>` → Displays the manual page of a command.
- `<command> --help` → Displays usage information for a command.
