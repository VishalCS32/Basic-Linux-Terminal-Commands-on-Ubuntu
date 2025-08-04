# 🐧 Basic Linux Terminal Commands on Ubuntu

This repository provides a quick reference for **essential Linux commands** commonly used in Ubuntu.  
These commands will help beginners navigate, manage files, install packages, and perform basic administrative tasks.

---

## 📂 **1. File & Directory Management**

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Show current working directory | `pwd` |
| `ls` | List files and directories | `ls -l` |
| `cd` | Change directory | `cd /home/user/Documents` |
| `mkdir` | Create a new directory | `mkdir myfolder` |
| `rmdir` | Remove an empty directory | `rmdir oldfolder` |
| `rm -r` | Remove a directory and its contents | `rm -r myfolder` |
| `touch` | Create an empty file | `touch file.txt` |
| `cp` | Copy files or directories | `cp file.txt backup.txt` |
| `mv` | Move or rename files/directories | `mv file.txt /home/user/Desktop` |
| `find` | Search for files/directories | `find /home -name file.txt` |

---

## 📄 **2. File Viewing & Editing**

| Command | Description | Example |
|---------|-------------|---------|
| `cat` | Display file content | `cat file.txt` |
| `less` | View file content one page at a time | `less file.txt` |
| `head` | Show first lines of a file | `head -n 10 file.txt` |
| `tail` | Show last lines of a file | `tail -n 10 file.txt` |
| `nano` | Edit file using Nano editor | `nano file.txt` |
| `vim` | Edit file using Vim editor | `vim file.txt` |

---

## 📦 **3. Package Management (APT)**

| Command | Description | Example |
|---------|-------------|---------|
| `sudo apt update` | Update package lists | `sudo apt update` |
| `sudo apt upgrade` | Upgrade installed packages | `sudo apt upgrade` |
| `sudo apt install` | Install a package | `sudo apt install curl` |
| `sudo apt remove` | Remove a package | `sudo apt remove firefox` |
| `sudo apt autoremove` | Remove unused dependencies | `sudo apt autoremove` |

---

## ⚡ **4. System Information & Monitoring**

| Command | Description | Example |
|---------|-------------|---------|
| `uname -a` | Show system information | `uname -a` |
| `top` | Display running processes | `top` |
| `htop` | Interactive process viewer (install first) | `htop` |
| `df -h` | Show disk usage | `df -h` |
| `du -sh` | Show size of current directory | `du -sh` |
| `free -h` | Show memory usage | `free -h` |
| `uptime` | Show system uptime | `uptime` |

---

## 🌐 **5. Network Commands**

| Command | Description | Example |
|---------|-------------|---------|
| `ping` | Check network connectivity | `ping google.com` |
| `ifconfig` | Display network interfaces (needs `net-tools`) | `ifconfig` |
| `ip a` | Show network interfaces and IP addresses | `ip a` |
| `curl` | Fetch data from URLs | `curl https://example.com` |
| `wget` | Download files from the web | `wget https://example.com/file.zip` |
| `netstat -tuln` | Show open ports (needs `net-tools`) | `netstat -tuln` |

---

## 🔒 **6. Permissions & Ownership**

| Command | Description | Example |
|---------|-------------|---------|
| `chmod` | Change file permissions | `chmod 755 script.sh` |
| `chown` | Change file owner | `sudo chown user:user file.txt` |
| `ls -l` | View file permissions | `ls -l` |

---

## 👑 **7. User & Group Management**

| Command | Description | Example |
|---------|-------------|---------|
| `whoami` | Show current logged-in user | `whoami` |
| `id` | Show user and group IDs | `id` |
| `adduser` | Add a new user | `sudo adduser newuser` |
| `usermod` | Modify a user account | `sudo usermod -aG sudo newuser` |
| `passwd` | Change user password | `passwd` |

---

## 🗃️ **8. Archive & Compression**

| Command | Description | Example |
|---------|-------------|---------|
| `tar -czvf` | Create a tar.gz archive | `tar -czvf backup.tar.gz myfolder` |
| `tar -xzvf` | Extract a tar.gz archive | `tar -xzvf backup.tar.gz` |
| `zip -r` | Create a zip file | `zip -r backup.zip myfolder` |
| `unzip` | Extract a zip file | `unzip backup.zip` |

---

## 🔥 **9. Process Management**

| Command | Description | Example |
|---------|-------------|---------|
| `ps aux` | Show running processes | `ps aux` |
| `kill` | Kill a process by PID | `kill 1234` |
| `killall` | Kill a process by name | `killall firefox` |
| `jobs` | List background jobs | `jobs` |
| `fg` | Bring job to foreground | `fg` |
| `bg` | Resume job in background | `bg` |

---

## 🛠️ **10. Useful Shortcuts**

- `Ctrl + C` → Stop current command  
- `Ctrl + Z` → Suspend current process  
- `Ctrl + D` → Logout from terminal  
- `!!` → Run last command again  
- `history` → Show command history  
- `!n` → Run command from history by number  

---


