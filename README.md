
=============================
     Linux Command Cheat Sheet
=============================

**Basic Commands:**

- `sudo [command]`: Run a command with superuser privileges.
- `nohup [command]`: Run a command that persists even after the terminal is closed.
- `man [command]`: Display the manual page for a command.
- `[command] &`: Run a command in the background.
- `>> [fileA]`: Append output to a file (preserving existing contents).
- `> [fileA]`: Overwrite contents of a file with output.
- `echo -n`: Display text without a newline.
- `xargs`: Build and execute command lines from standard input.

**Job Control:**

- `1>2&`: Redirect stdout to stderr.
- `fg %N`: Bring a background task to the foreground.
- `jobs`: List active jobs.
- `ctrl-z`: Suspend the current task.

**File Utilities:**

- `tr -d`: Translate or delete characters.
- `uniq -c -u`: Report or omit repeated lines.
- `split -l`: Split a file into pieces.
- `wc -w`: Print word count.
- `head -n`: Output the first part of files.
- `cut -s`: Remove section from a file.
- `diff -q`: File compare, line by line.
- `join -i`: Join lines of two files on a common field.
- `more, less`: View file content one page at a time.
- `sort -n`: Sort lines in a text file.
- `comm -3`: Compare two sorted files, line by line.
- `cat -s`: Concatenate files, squeezing multiple empty lines.
- `tail -f`: Output the last part of a file and follow changes.

**Directory Utilities:**

- `mkdir`: Create a directory.
- `rmdir`: Remove a directory.
- `find`: Search for a file.
- `ls -a -C -h`: List directory contents.
- `rm -r -f`: Remove files and directories.
- `locate -i`: Find files using an updatedb database.
- `cp -a -R -i`: Copy files or directories.
- `du -s`: Display disk usage.
- `file -b -i`: Identify file type.
- `mv -f -i`: Move files or directories.

**File Permission:**

- `chmod -c -R`: Change file permissions recursively.
- `touch -a -t`: Modify or create file timestamps.
- `chown -c -R`: Change file ownership recursively.
- `chgrp -c -R`: Change file group permission recursively.

**Disk Utilities:**

- `df -h, -i`: Display file system usage.
- `mkfs -t -V`: Create a file system.
- `resize2fs`: Update a file system after lvextend*.
- `fsck -A -N`: File system check and repair.
- `pvcreate`: Create a physical volume.
- `mount -a -t`: Mount a file system.
- `fdisk -l`: Edit disk partitions.
- `lvcreate`: Create a logical volume.
- `umount -f -v`: Unmount a file system.

**Memory & Processes:**

- `free -m`: Display free and used system memory.
- `killall`: Stop all processes by name.
- `sensors`: Display CPU temperature.
- `top`: Display current processes with real-time monitoring.
- `kill -1 -9`: Send signals to a process.
- `service [start|stop|restart]`: Manage or run sysV init scripts.
- `ps aux`: Display current processes with a snapshot.
- `dmesg -k`: Display system messages.

**Network:**

- `netstat -r -v`: Print network information, routing, and connections.
- `telnet`: User interface to the TELNET protocol.
- `tcpdump`: Dump network traffic.
- `ssh -i`: OpenSSH client.
- `ping -c`: Print routing packet trace to host network.

**Miscellaneous Commands:**

- `pwd -P`: Print current working directory.
- `bc`: High-precision calculator.
- `expr`: Evaluate expressions.
- `cal`: Print calendar.
- `export`: Assign or remove environment variables.
- \` [command]\`: Execute command and use the result.
- `date -d`: Print formatted date.
- `$[variable]`: Access the variable if set.

**File Compression:**

- `tar xvfz`: Create or extract .tar or .tgz files.
- `gzip, gunzip, zcat`: Create, extract, or view .gz files.
- `uuencode, uudecode`: Create or extract .Z files.
- `zip, unzip -v`: Create or extract .ZIP files.
- `rpm`: Create or extract .rpm files.
- `bzip2, bunzip2`: Create or extract .bz2 files.
- `rar`: Create or extract .rar files.

**File Editors:**

- `ex`: Basic editor.
- `vi`: Visual editor.
- `nano`: Pico clone.
- `view`: View file only.
- `emacs`: Extensible, customizable editor.
- `sublime`: Yet another text editor.
- `sed`: Stream editor.
- `pico`: Simple editor.

**Scripting:**

- `awk, gawk`: Pattern scanning.
- `tsh`: Tiny shell.
- `python`: Object-oriented programming language.
- `bash`: GNU Bourne-Again SHell.
- `ksh`: Korn shell.
- `php`: General-purpose scripting language.
- `csh, tcsh`: C shell.
- `perl`: Practical Extraction and Report Language.
- `source [file]`: Load any functions file into the current shell (requires the file to be executable).
