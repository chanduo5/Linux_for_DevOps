## Linux_for_DevOps ##


# 100 Basic Commands #



 - Print working directory.
   
       pwd
   
- List directory contents.

      ls 

- Change directory.
  
      cd
  
- Make directory.

      mkdir 

- Remove directory.
  
      rmdir 

- Copy files or directories.
  
      cp 

- Move/rename files or directories.
  
      mv 

- Remove files or directories.
  
      rm 

- Create a new empty file.

      touch
  
- Concatenate and display file content.
  
      cat 

 - Display a line of text.
   
       eho

- Show the manual for a command.

      man 

- Show the current user.

      whoami 

- Show or set the system's hostname.

      hostname 

- Report file system disk space usage.

      df 

- Estimate file space usage.
  
      du 

- Display memory usage.

      free

 - Display task manager.

       top

- Report a snapshot of current processes.

      ps

- Terminate a process by PID.
   
      kill 

- Change file owner and group.
  
      chown 

- Change file modes or Access Control Lists.

      chmod 

- Create hard and symbolic links.

      ln 

- Show system information.

      uname 

- Archive files.

      tar 

- Compress files.

      gzip 

- Decompress files.

      gunzip 

- Package and compress files.

      zip 

- Extract compressed files.


      unzip 

- Send ICMP ECHO_REQUEST to network hosts.

      ping 

- Non-interactive network downloader.

      wget 

- Transfer data from or to a server.

      curl 

- OpenSSH client (remote login program).

      ssh 

- Secure copy (remote file copy program).

      scp 

- File Transfer Protocol client.

      ftp 

- Remote file and directory synchronization.

      rsync 

- Mount a file system.

       mount 

- Unmount file systems.

      umount 

 - Search for files in a directory hierarchy.

       find

- Print lines that match patterns.

      grep 

- Stream editor for filtering and transforming text.

      sed 

- Pattern scanning and processing language.

      awk 

- Sort lines of text files.

      sort 

- Report or omit repeated lines.

      uniq 

- Output the first part of files.

      head 

- Output the last part of files.

      tail 

- Print newline, word, and byte counts for each file.

      wc 

- Compare files line by line.

      diff 

- Apply a diff file to an original.

      patch 

- Schedule periodic background jobs.

      crontab




# Intermediate Commands #


- Configure a network interface.
  
      ifconfig 

- Print network connections, routing tables, interface statistics.

      netstat

 - Print the route packets take to network host.

       traceroute 

- Administration tool for IPv4 packet filtering and NAT.

      iptables

- Control the systemd system and service manager.

      systemctl
 
- Query and display messages from the journal.
 
      journalctl
 
- Define or display aliases.
  
      alias 

- Remove alias definitions.

      unalias 

- Text editor in the terminal.

      nano 

- Text editor in the terminal.

      vi 

- Improved vi text editor.

      vim

- Text editor with GUI and terminal versions.

      emacs 

- Execute a command as another user.

      sudo 

- Switch user.

      su 

- Create a new user.

      useradd 

- Modify a user account.

      usermod 

- Delete a user account.

      userdel 

- Create a new group.

      groupadd 

- Modify a group.

      groupmod 

- Delete a group.

      groupdel 

- Change user password.

      passwd 

- Change file permissions.

      chmod 

- Change file attributes.
  
      chattr 

- List file attributes on a Linux file system.
  
      lsattr 

- Get locale-specific information.

      locale 

- Display or set the date and time.

       date 

- Display a calendar.

      cal 

- An arbitrary precision calculator language.

      bc 

- An arbitrary precision reverse-polish calculator.

      dc 

- Interactive process viewer.

      htop 

- Terminal multiplexer.

      screen 

- Terminal multiplexer.

      tmux 

- Generate SSH keys.

      ssh-keygen 

- Securely copy files between hosts.

      scp 

- Secure File Transfer Protocol.

      sftp 

- Rocket-fast system for log processing.

      rsyslog 

- Command-line packet analyzer.

      tcpdump 

- Show/manipulate routing, devices, policy routing, and tunnels.

       ip 

- Show IP addresses assigned to all interfaces.

      ip addr 

- Show network interfaces.

      ip link 

- Show routing table.

      ip route 

- Manipulate the system ARP cache.

       arp 

- Control the system hostname.

      hostnamectl 

- List information about block devices.

      lsblk 

- Locate/print block device attributes.

      blkid 

- A partition manipulation program.

      parted 

- Build a Linux file system.

      mkfs 

- Adjust tunable file system parameters on ext2/ext3/ext4 file systems.

      tune2fs 

- File system consistency check and repair.

       fsck 

- Check a Linux ext2/ext3/ext4 file system.

      e2fsck 

# Basic Theory #

 ## Linux is a family of open-source Unix-like operating systems based on the Linux kernel. It is typically packaged in a form known as a Linux distribution for both desktop and server use. Some of the popular distributions include Ubuntu, Fedora, CentOS, and Debian. ##


Kernel: The core of the Linux operating system, responsible for managing the system's hardware and resources. It provides basic services for all other parts of the operating system.

Shell: A command-line interface that allows users to interact with the operating system by typing commands. Common shells include Bash, Zsh, and Fish.

File System: Linux uses a hierarchical file system structure. Everything in Linux is a file, including hardware devices and system resources.

Package Management: Linux distributions use package managers to install, update, and remove software. Examples include APT (Advanced Package Tool) for Debian-based distributions and YUM (Yellowdog Updater, Modified) for RedHat-based distributions.

Linux is known for its security, stability, and flexibility. It's widely used in servers, supercomputers, and embedded systems, and has a strong community of developers and users who contribute to its ongoing development and improvement.
