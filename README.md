# init
#### This is the init project done @ 42 Paris
[100/100][Subject] (https://github.com/ablin42/init/blob/master/init.en.pdf)

## This project will introduce you to the basic topics of DevOps. Provided by the slash16 team.

#### General infos
Answers can be either a command, a command output, or a simple deduction.
The network part MUST be done on a mac at 42, the system and scripts part are supposed to be ran in a VM running debian

### Objectives
> - Unix 
> - System Administration 

### Skills
> - Network & system administration
> - Unix 

### Restrictions
> - Only terminal commands are authorized
> - Output expected: command/command output/deduction
> - Scripts must be executable

### Network
> - 1. Get the list of the network interfaces of the machine without displaying any detail
for these interfaces. Only the list of names.
> - 2. Identify the IP address of the Ethernet interface
> - 3. Identify the MAC address of the Wi-Fi card
> - 4. Identifiy the default gateway in the routing table
> - 5. Identify the IP address of the DNS that responds to the following url: slash16.org
> - 6. Get the complete path of the file that contains the IP address of the DNS server
you’re using
> - 7. Query an external DNS server on the slash16.org domain name (ie. : google
8.8.8.8)
> - 8. Are the returned IP addresses similiar?
> - 9. Do the same with 42.fr, what do you notice?
> - 10.Identify the network devices between your computer and the slash16.org domain
> - 11. Use the output of the previous command to find the name and IP address of the
device that makes the link between you (local network) and the outside world
> - 12. Check that the server with the 10.51.1.253 IP address is reachable from your
computer
> - 13. Figure out the server type
> - 14. Use the Reverse DNS to find out the name of the server linked to the 10.51.1.81
IP address
> - 15. What file contains the local DNS entries?
> - 16. Make the 46.19.122.85 address reroute to intra.42.fr

### System
> - 1. In what file can you find the installed version of your Debian?
> - 2. What command can you use to rename your system?
> - 3. What file has to be modified to make it permanent?
> - 4. What command gives you the time since your system was last booted?
> - 5. Name the command that determines the state of the SSH service
> - 6. Name the command that reboots the SSH service
> - 7. Figure out the PID of the SSHD service
> - 8. What file contains the RSA keys that are authorized to connect via SSH?
> - 9. What command lets you know who is connected to the System?
> - 10. Name the command that lists the partition tables of external devices
> - 11. Name the command that displays the available space left on the system
> - 12. Figure out the exact size of each folder of /var
> - 13. Name the command that find currently running processes
> - 14. Run the ‘tail -f /var/log/syslog‘ command in background
> - 15. Find the command that kills the background command’s process
> - 16. Find the service which makes it possible to run specific tasks following a regular
schedule
> - 17. Find the command which gives the list of firewall rules
> - 18. With the previous command, authorize only IP addresses from 10.0.0.0/8 to connect to your system
> - 19. With the previous command, forbid all others

### Scripting
> - 1. Write a script which displays only the login, UID and Path of each entry of the
/etc/passwd file
> - 2. Write a script which updates all the package sources, then all the packages, and then
logs everything in a file named /var/log/update_script.log. Create a scheduled
task for this script, once per week at 4 AM
> - 3. Write a script which displays the list of files from the folder given as parameter,
sorted by size
> - 4. Write a script which monitors the modifications made to the /etc/crontab file and
sends an e-mail to root if the file is modified. Create a scheduled task to run this
script everyday at midnight
> - 5. Write a script which displays 42

