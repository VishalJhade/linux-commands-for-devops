# 🐧 Linux Commands for DevOps

Welcome to my Linux learning log! I'm currently learning Linux as the first step in my DevOps journey. This repository documents all the commands I learn — with examples, use cases, and explanations.

---

## 📁 File and Directory Commands

| Command            | Description                                      | Example                              |
|--------------------|------------------------------------------------|------------------------------------|
| `ls`               | List files and directories in current folder   | `ls -l` (detailed list)             |
| `pwd`              | Print current working directory                  |                                    |
| `cd <folder>`      | Change directory                                 | `cd Documents/`                     |
| `mkdir <folder>`   | Create a new directory                           | `mkdir projects`                    |
| `touch <file>`     | Create a new empty file                          | `touch notes.txt`                   |
| `rm <file>`        | Remove/delete a file                             | `rm oldfile.txt`                    |
| `rm -r <folder>`   | Remove a directory and its contents recursively | `rm -r temp_folder`                 |
| `cp <source> <destination>` | Copy files or folders                     | `cp file.txt backup.txt`            |
| `mv <source> <destination>` | Move or rename files or folders           | `mv oldname.txt newname.txt`        |
| `find <path> -name <filename>` | Search for files by name               | `find . -name "*.log"`              |
| `file <filename>`  | Determine file type                              | `file script.sh`                    |
| `stat <file>`      | Show detailed info about a file                  | `stat notes.txt`                    |
| `head <file>`      | Show first 10 lines of a file                     | `head log.txt`                     |
| `tail <file>`      | Show last 10 lines of a file                      | `tail -f /var/log/syslog` (follow) |
| `cat <file>`       | Display contents of a file                        | `cat readme.md`                    |

---

### 🔐 Permissions, Users & Groups

| Command     | Description                            | Example                             |
|-------------|----------------------------------------|-------------------------------------|
| chmod       | Change file permissions                | `chmod 755 script.sh`               |
| chown       | Change file owner and group            | `chown user:group file.txt`         |
| chgrp       | Change group ownership                 | `chgrp developers file.txt`         |
| umask       | Set default permission for new files   | `umask 022`                         |
| id          | Display user and group IDs             | `id`                                |
| groups      | Show groups a user belongs to          | `groups username`                   |
| useradd     | Add a new user                         | `useradd newuser`                   |
| usermod     | Modify a user account                  | `usermod -aG sudo newuser`          |
| userdel     | Delete a user account                  | `userdel newuser`                   |
| groupadd    | Create a new group                     | `groupadd devteam`                  |
| groupdel    | Delete a group                         | `groupdel devteam`                  |
| groupmod    | Modify a group                         | `groupmod -n newgroup oldgroup`     |
| passwd      | Change user password                   | `passwd newuser`                    |
| whoami      | Show current user                      | `whoami`                            |
| su          | Switch user                            | `su - username`                     |
| sudo        | Execute command as superuser           | `sudo apt update`                   |

---

### 🛠️ Common Utilities

| Command     | Description                                 | Example                                 |
|-------------|---------------------------------------------|-----------------------------------------|
| cat         | Concatenate and display file content        | `cat file.txt`                          |
| nano        | Simple text editor                          | `nano file.txt`                         |
| vim         | Advanced text editor                        | `vim file.txt`                          |
| grep        | Search for patterns in files                | `grep 'error' logfile.txt`              |
| find        | Search for files in a directory hierarchy   | `find /var -name "*.log"`               |
| head        | Display first lines of a file               | `head -n 10 file.txt`                   |
| tail        | Display last lines of a file                | `tail -n 10 file.txt`                   |
| less        | View file content one page at a time        | `less file.txt`                         |
| touch       | Create an empty file or update timestamp    | `touch newfile.txt`                     |
| echo        | Display message or variable value           | `echo "Hello World"`                    |
| wc          | Count lines, words, and bytes               | `wc -l file.txt`                        |
| sort        | Sort lines in a file                        | `sort file.txt`                         |
| uniq        | Filter out repeated lines                   | `uniq file.txt`                         |
| cut         | Remove sections from each line              | `cut -d':' -f1 /etc/passwd`             |
| tr          | Translate or delete characters              | `tr 'a-z' 'A-Z' < file.txt`             |
| tee         | Redirect output to multiple files/displays  | `echo "Log" | tee logfile.txt`          |

---

### 📈 Process & System Monitoring

| Command     | Description                         | Example                           |
|-------------|-------------------------------------|-----------------------------------|
| top         | Display real-time system processes  | `top`                             |
| htop        | Interactive process viewer          | `htop`                            |
| ps          | Report process status               | `ps aux`                          |
| kill        | Terminate a process by PID          | `kill 1234`                       |
| killall     | Terminate processes by name         | `killall firefox`                |
| df          | Report disk space usage             | `df -h`                           |
| du          | Estimate file space usage           | `du -sh /home/user`               |
| free        | Display memory usage                | `free -m`                         |
| uptime      | Show system uptime                  | `uptime`                          |
| vmstat      | Report virtual memory statistics    | `vmstat 1`                        |
| iostat      | CPU and I/O statistics              | `iostat`                          |
| sar         | System activity report              | `sar -u 1 3`                      |

---

## 🚀 My DevOps Learning Progress

- ✅ Week 1: Linux basics, navigation, file handling
- 🔄 Updating regularly with new commands

---

## 📚 Why I'm Doing This

I'm a BTech CSE student (2nd year, soon to be 3rd year), aiming for a DevOps role. I'm sharing my journey publicly to stay consistent and help others too.

---

## 🔗 Connect With Me

- LinkedIn: [linkedin.com/in/vishal-jhade-94b1b1299](https://www.linkedin.com/in/vishal-jhade-94b1b1299)
- Portfolio (soon): Coming soon!
