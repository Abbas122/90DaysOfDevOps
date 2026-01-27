
Linux Command Cheat Sheet – DevOps Essentials
1. Process Management Commands

ps aux – Displays all running processes with details like CPU and memory usage.
top – Shows real-time system resource usage and running processes.
htop – An interactive and user-friendly version of top.
kill <PID> – Sends a signal to stop a process by its PID.
kill -9 <PID> – Forcefully terminates a process that is not responding.

2. File System Commands
ls – Lists files and directories in the current location.
cd <directory> – Changes the current working directory.
pwd – Shows the full path of the current directory.
cp source destination – Copies files or directories.
mv source destination – Moves or renames files and directories.
rm -r <directory> – Deletes files or directories permanently.
df -h – Displays disk space usage in human-readable format.
du -sh <directory> – Shows the size of a directory.

3. Networking & Troubleshooting Commands
ip a – Displays network interfaces and IP addresses.
ping <host> – Checks network connectivity to a host.
curl <url> – Tests HTTP/HTTPS endpoints from the command line.
wget <url> – Downloads files from the internet.
ss -tuln – Shows listening ports and network services.
netstat -tuln – Displays network connections and open ports (legacy).

traceroute <host> – Traces the path packets take to reach a host.
