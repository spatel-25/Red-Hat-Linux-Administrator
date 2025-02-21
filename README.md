# Basic Linux Knowledge
1. What is Linux? What is the difference between Linux and Windows?
2. Explain the basic directory structure of Linux.
`/home, /etc, /bin, /var, /tmp, /usr, etc.`
3. How would you create a new user and set its password?
`useradd, passwd`
4. What are file permissions in Linux? How do you change them?
`chmod, chown, chgrp`
5. What is a process in Linux? How do you view running processes?
`ps, top, htop`
6. Explain the use of the *ls* and *cp* commands.
7. How do you list all files, including hidden files, in a directory?
`ls -a`
8. What is the difference between rm and rmdir commands?
9. How do you create a symbolic link in Linux?
`ln -s`
10. How do you display the content of a file using the command line?
`cat, more, less, head, tail`
11. What is the difference between a hard link and a soft link in Linux?
12. Explain the Linux directory structure. What is the purpose of directories like /bin, /etc, /var, /home, and /tmp?
13. What are some common commands to list files and directories in Linux?
14. What are file permissions in Linux, and how do you change them?
15. How do you create a new user and set its password in Linux?
16. Explain how the ps command works. How do you list all processes running on a system?
17. What is the difference between the shutdown and reboot commands?
18. What are the differences between tar, gzip, and bzip2?
19. What is the purpose of the /etc/passwd file?
20. What is the role of the /etc/fstab file?

# Red Hat Linux Specific
1. How does Red Hat Linux handle package management, and what tools do you use?
2. What is YUM (Yellowdog Updater, Modified), and how does it differ from RPM?
3. What is SELinux, and how do you configure it?
4. Explain the purpose of systemd in Red Hat-based systems.
5. How do you check the status of a service in Red Hat Linux using systemctl?
6. How would you configure a static IP address on a Red Hat system?
7. What are the differences between RHEL 7 and RHEL 8?
8. How do you update the system using dnf or yum in RHEL 8?
9. What is the role of firewalld in Red Hat, and how do you configure it?

# Networking
1. How would you configure a network interface on a Red Hat Linux system?
2. What are the different types of network interfaces in Linux?
3. Explain how you would troubleshoot network connectivity issues in Linux.
4. What is the purpose of iptables in Linux?
5. How would you configure a DNS server on Red Hat Linux?
6. Explain the difference between a static IP, dynamic IP, and DHCP.
7. What is the netstat command, and how do you use it for troubleshooting?

# Disk Management and Filesystems
1. How do you create and manage disk partitions in Linux?
2.  Explain the LVM (Logical Volume Management) in Linux and how it is used.
3.  What are the common file systems supported by Red Hat Linux?
4.  How do you mount a filesystem in Red Hat Linux?
5.  How do you resize an ext4 partition?
6.  What is the difference between ext4, xfs, and btrfs file systems?
7.  How do you check disk space usage in Linux?

# Security and User Management
1. How do you configure user authentication in Linux?
2. What is sudo, and how do you configure it for users?
3. How do you manage SSH keys for secure login?
4. Explain the concept of sudoers file and how you modify it.
5. What is PAM (Pluggable Authentication Modules)?
6. What is the importance of firewall configurations in Red Hat Linux?
7. How do you manage SELinux in enforcing, permissive, and disabled modes?
8. What are Linux groups, and how do you manage group permissions?

# Process Management and Performance
1. How do you monitor the performance of a Linux system?
2. What tools would you use to troubleshoot CPU and memory utilization issues?
3. How do you manage background processes in Linux?
4. Explain how you would find and kill a process in Linux.
5. What is top or htop, and how do you use them to monitor system performance?
6. What is nice and renice in Linux?
7. Explain the significance of the vmstat and iostat commands.

# Backup and Recovery
1. How would you perform a backup of a Red Hat Linux system?
2. What is the difference between full, incremental, and differential backups?
3. What tools are available in Linux for backing up and restoring data?
4. How would you restore a system using a backup in case of failure?
5. How do you schedule backups using cron?

# Automation and Scripting
1. What is the purpose of shell scripting in Linux, and how do you create a script?
2. How do you schedule tasks using cron and at in Linux?
3. Explain how environment variables work in a shell.
4. What is a bash script, and how would you make it executable?
5. How do you debug a shell script that is not running correctly?

# System Maintenance
1. How do you monitor system logs in Linux?
2. What is the significance of journalctl in Red Hat Linux?
3. How do you handle system updates in a production environment?
4. How would you perform routine system maintenance, such as clearing cache or rotating logs?

# Troubleshooting
1. What steps would you take to troubleshoot a system that is not booting?
2. How would you debug a service that is failing to start on a Red Hat system?
3. How do you recover from a system crash or kernel panic?
4. Explain the process of recovering a deleted file in Linux.
5. How do you check system logs for errors in Red Hat Linux?


# Advanced Level (Expert)
1. What is SELinux (Security-Enhanced Linux), and how do you manage it?
`getenforce, setenforce, /etc/selinux/config`
2. How do you configure and manage a firewall in Red Hat Linux using firewalld?
`firewall-cmd, zones, services`
3. Explain LVM (Logical Volume Manager) in Linux. How do you create, extend, and manage LVM volumes?
`pvcreate, vgcreate, lvcreate, lvextend`
4. What is the role of systemd and journalctl in RHEL 7/8 for service management and logging?
5. How would you troubleshoot a service that is failing to start using systemd?
`systemctl status, journalctl -xe, checking logs in /var/log`
6. How do you manage kernel modules in Red Hat Linux?
`lsmod, modprobe, rmmod`
7. Explain how to optimize disk I/O performance on Red Hat Linux systems.
`Tuning iostat, vmstat, filesystem optimization, RAID configurations`
8. What is the process for creating and managing a swap space in Linux?
`swapon, swapoff, /etc/fstab`
9. How do you schedule recurring tasks in Linux using cron and at?
`crontab -e, at commands, managing cron jobs`
10. What is the difference between yum and dnf in RHEL 8?
11. What is the iptables command used for?
`Configuring network filtering, port forwarding, etc.`
12. What are the different file systems supported by Linux?
`ext4, xfs, btrfs, zfs`
13. How do you troubleshoot network connectivity issues in Red Hat Linux?
`ping, netstat, ss, ip, traceroute`
14. How would you implement high availability (HA) clustering in Red Hat Linux?
`Using Pacemaker, Corosync, drbd`
15. How do you upgrade a Red Hat Linux system from one major release to another (e.g., RHEL 7 to RHEL 8)?
16. Explain the concept of a kernel panic in Linux and how to recover from it.
17. What is the process for setting up RAID on Linux?
`mdadm, RAID levels, disk arrays`
18. How do you implement and manage system backups and disaster recovery in Linux?
`Backup strategies (rsync, Bacula, tar), restore procedures`
19. What are some tools and techniques for monitoring Linux system performance?
`top, htop, vmstat, sar, nmon`
20. How do you secure SSH access on a Linux server?
`Using SSH keys, disabling root login, configuring sshd_config, fail2ban`
