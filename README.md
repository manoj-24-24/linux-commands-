 

# Linux Commands for Cybersecurity

## 📁 File & Directory Commands

| Command | Purpose | Example |
|---|---|---|
| `pwd` | Show current directory | `pwd` |
| `ls` | List files and directories | `ls -la` |
| `cd` | Change directory | `cd /var/log` |
| `mkdir` | Create a directory | `mkdir tools` |
| `touch` | Create an empty file | `touch notes.txt` |
| `cp` | Copy files/directories | `cp file.txt backup.txt` |
| `mv` | Move or rename files | `mv old.txt new.txt` |
| `rm` | Remove files | `rm file.txt` |
| `find` | Search for files | `find /var/log -name "*.log"` |

## 🔐 Permissions & Ownership

| Command | Purpose | Example |
|---|---|---|
| `chmod` | Change file permissions | `chmod 600 secret.txt` |
| `chown` | Change file owner | `sudo chown user file.txt` |
| `umask` | Set default permissions | `umask 027` |

## ⚙️ Process Management

| Command | Purpose | Example |
|---|---|---|
| `ps` | Display running processes | `ps aux` |
| `top` | Monitor processes | `top` |
| `htop` | Interactive process viewer | `htop` |
| `kill` | Terminate a process | `kill PID` |
| `systemctl` | Manage services | `systemctl status ssh` |

## 📜 Log Analysis

| Command | Purpose | Example |
|---|---|---|
| `cat` | Display file contents | `cat auth.log` |
| `less` | Read large files | `less /var/log/auth.log` |
| `grep` | Search text | `grep "Failed" auth.log` |
| `tail` | Show end of file | `tail -f auth.log` |
| `head` | Show beginning of file | `head auth.log` |

## 👤 User Information

| Command | Purpose | Example |
|---|---|---|
| `whoami` | Show current user | `whoami` |
| `id` | Show user/group IDs | `id` |
| `who` | Show logged-in users | `who` |
| `last` | Show login history | `last` |

> ⚠️ Use commands such as `rm`, `kill`, `chmod`, `chown`, and `systemctl` carefully, especially when using `sudo`.

