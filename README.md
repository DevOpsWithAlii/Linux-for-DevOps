# Linux-for-DevOps.

Here’s your cleaned-up list of commands in **Markdown format** with headings for better organization.. Each command is listed only once, and the structure is optimized for readability.

# 📌 Linux Commands Practice Notes for DevOps Engineers

## 📂 Navigation and File Management
| Command | Description |
|---------|-------------|
| `cd /` | Navigate to the root directory. |
| `ls` | List directory contents. |
| `cd home` | Move to the home directory. |
| `cd ..` | Move up one directory level. |
| `pwd` | Print the current working directory. |
| `mkdir devops` | Create a directory named `devops`. |
| `rm filename` | Remove a file. |
| `rmdir directory` | Remove an empty directory. |
| `touch file.txt` | Create an empty file. |
| `vim file.txt` | Open file in Vim editor. |
| `cat file.txt` | Display file contents. |

## 👥 User and Group Management
| Command | Description |
|---------|-------------|
| `sudo useradd -m username` | Create a new user with a home directory. |
| `sudo passwd username` | Set a password for the user. |
| `sudo userdel username` | Delete a user. |
| `sudo groupadd groupname` | Create a new group. |
| `sudo gpasswd -a user group` | Add a user to a group. |
| `cat /etc/passwd` | View system users. |
| `cat /etc/group` | View groups. |

## 🔄 System and Process Management
| Command | Description |
|---------|-------------|
| `sudo apt update && sudo apt upgrade` | Update and upgrade system packages. |
| `sudo apt install package-name` | Install a package. |
| `sudo systemctl status service-name` | Check the status of a service. |
| `sudo systemctl start/stop/restart service-name` | Manage system services. |
| `top` | Display running processes. |
| `df -h` | Show disk space usage. |
| `du -sh directory` | Show directory size. |
| `uptime` | Display system uptime. |

## 📝 Text Processing Commands
| Command | Description |
|---------|-------------|
| `head -n 5 file.txt` | Show first 5 lines of a file. |
| `tail -n 5 file.txt` | Show last 5 lines of a file. |
| `awk '/pattern/ {print $0}' file.txt` | Print lines matching a pattern. |
| `sed 's/old/new/g' file.txt` | Replace `old` with `new` in a file. |
| `wc -l file.txt` | Count lines in a file. |
| `sort file.txt` | Sort file contents alphabetically. |
| `grep keyword file.txt` | Search for a keyword in a file. |

## 🌐 Networking Commands
| Command | Description |
|---------|-------------|
| `ping -c 4 google.com` | Ping a website to test connectivity. |
| `host google.com` | Perform a DNS lookup. |
| `dig google.com` | Query DNS records. |
| `ifconfig` | Display network interfaces. |
| `ip a` | Show IP addresses. |

## 🛠 Miscellaneous Commands
| Command | Description |
|---------|-------------|
| `alias ll='ls -la'` | Create a shortcut for `ls -la`. |
| `unalias ll` | Remove an alias. |
| `tree` | Display directory structure as a tree. |
| `date` | Show current date and time. |
| `whoami` | Show current logged-in user. |
| `who` | Display all logged-in users. |

---

📌 **Pro Tip:** Regular practice of these commands will improve efficiency in Linux system administration and DevOps workflows. 🚀

Would you like to add any examples or expand specific sections? 😊
