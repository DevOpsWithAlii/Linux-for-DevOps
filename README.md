# Linux-for-DevOps.

Here’s your cleaned-up list of commands in **Markdown format** with headings for better organization. Each command is listed only once, and the structure is optimized for readability.

```markdown
# Linux Commands Practice Notes

## Navigation and File Management
- `cd /` - Navigate to the root directory.
- `ls` - List directory contents.
- `cd home` - Navigate to the home directory.
- `cd ..` - Move up one directory level.
- `cd .ssh` - Navigate to the `.ssh` directory.
- `exit` - Exit the current shell.
- `clear` - Clear the terminal screen.
- `history` - Display command history.
- `pwd` - Print the current working directory.
- `mkdir devops` - Create a directory named `devops`.
- `rm one.txt` - Remove the file `one.txt`.
- `sudo rm two.txt` - Remove the file `two.txt` with superuser privileges.
- `sudo rmdir devops` - Remove the `devops` directory.
- `touch one.txt` - Create an empty file named `one.txt`.
- `touch two.txt` - Create an empty file named `two.txt`.
- `vim one.txt` - Edit `one.txt` using the Vim text editor.
- `cat one.txt` - Display the contents of `one.txt`.
- `sudo chmod 777 one.txt` - Change file permissions to `777` for `one.txt`.
- `sudo chmod 400 one.txt` - Change file permissions to `400` for `one.txt`.
- `sudo chmod 664 one.txt` - Change file permissions to `664` for `one.txt`.
- `sudo chmod +x one.txt` - Add execute permission to `one.txt`.
- `sudo chown ali2 one.txt` - Change ownership of `one.txt` to `ali2`.
- `sudo chmod 750 ubuntu` - Change directory permissions to `750` for `ubuntu`.
- `grep hello -r /home/ubuntu/` - Search for the word `hello` recursively in `/home/ubuntu/`.
- `grep students -r /home/ubuntu/` - Search for the word `students` recursively in `/home/ubuntu/`.
- `grep nginx -r /` - Search for the word `nginx` recursively in the root directory.
- `find /home -name "2nd.txt"` - Find the file `2nd.txt` in `/home`.
- `find /home -name "1st.txt"` - Find the file `1st.txt` in `/home`.

## User and Group Management
- `sudo userdel ali` - Delete the user `ali`.
- `sudo useradd -m user01` - Create a new user `user01` with a home directory.
- `sudo passwd user01` - Set a password for `user01`.
- `sudo useradd -m ali` - Create a new user `ali` with a home directory.
- `sudo useradd -m ali2` - Create a new user `ali2` with a home directory.
- `sudo useradd -m ali3` - Create a new user `ali3` with a home directory.
- `sudo passwd ali` - Set a password for `ali`.
- `sudo passwd ali2` - Set a password for `ali2`.
- `sudo passwd ali3` - Set a password for `ali3`.
- `sudo groupadd devops01` - Create a new group `devops01`.
- `sudo groupadd tester01` - Create a new group `tester01`.
- `sudo gpasswd -a ali devops01` - Add user `ali` to the group `devops01`.
- `sudo gpasswd -a ali2 tester01` - Add user `ali2` to the group `tester01`.
- `sudo gpasswd -a ali3 tester01` - Add user `ali3` to the group `tester01`.
- `cat /etc/passwd` - Display the contents of `/etc/passwd`.
- `cat /etc/group` - Display the contents of `/etc/group`.
- `sudo rm -rf /home/ali /home/ali2 /home/ali3 /home/user01` - Remove user directories.

## System and Process Management
- `sudo apt-get update` - Update the package list.
- `sudo apt-get upgrade` - Upgrade installed packages.
- `sudo apt-get install nginx` - Install the `nginx` package.
- `sudo apt-get purge nginx` - Remove the `nginx` package and its configuration files.
- `systemctl status nginx` - Check the status of the `nginx` service.
- `sudo systemctl stop nginx` - Stop the `nginx` service.
- `sudo systemctl start nginx` - Start the `nginx` service.
- `top` - Display real-time system processes.
- `ps` - Display current processes.
- `df` - Display disk space usage.
- `du` - Display directory space usage.
- `cron` - Manage cron jobs.
- `ifconfig` - Display network interface configuration.
- `ip` - Show or manipulate routing, devices, and tunnels.
- `uptime` - Display system uptime.
- `sudo` - Execute a command with superuser privileges.
- `man man` - Display the manual page for the `man` command.

## Text Processing and Utilities
- `head -n 5 1st.txt` - Display the first 5 lines of `1st.txt`.
- `tail -n 2 1st.txt` - Display the last 2 lines of `1st.txt`.
- `awk '/I/ {print $0}' 2nd.txt` - Search for lines containing `I` in `2nd.txt`.
- `sed 's/D/DD/' 2nd.txt` - Replace `D` with `DD` in `2nd.txt`.
- `wc 1st.txt` - Count lines, words, and characters in `1st.txt`.
- `sort 1st.txt` - Sort the contents of `1st.txt`.
- `grep boys -r /home` - Search for the word `boys` recursively in `/home`.
- `grep PowerManagerService: -r /home` - Search for `PowerManagerService:` recursively in `/home`.

## Networking
- `ping google.com` - Ping `google.com` to check connectivity.
- `host google.com` - Perform a DNS lookup for `google.com`.
- `dig google.com` - Query DNS information for `google.com`.
- `nmap` - Network exploration tool and port scanner.

## Miscellaneous
- `alias` - Display or create command aliases.
- `unalias` - Remove command aliases.
- `tree` - Display directory structure in a tree format.
- `date` - Display the current date and time.
- `whoami` - Display the current username.
- `who` - Display logged-in users.
```
