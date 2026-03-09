# Ex.3 Virtualization: Installation and Configuration of OracleVirtualBox & Kali Linux, and Execution of Linux Commands
# Aim
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and
execute fundamental Linux commands
# 3.a) Installation and Configuration of Oracle VirtualBox
# Aim
To install and configure Oracle VM VirtualBox.
# Pre-requisites:
Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space
# Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site

Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.

Choose Installation Options → Click Next.

Accept Network Interface Warning → Click Yes.

Click Install.

Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

Start Virtual Machine and provide ISO to install OS.

# Result:
Thus, Oracle VM VirtualBox was installed successfully.
# 3.b) Installation and Configuration of Kali Linux
# Aim 
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:

Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image
# Steps:

1.Download Kali Linux ISO:

Visit Kali Linux Official Site

Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

Open VirtualBox → Click New.

Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).

4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).

Choose Dynamically allocated.

Set Disk size to 20 GB or more.

5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.

Set Language, Region, Keyboard.

Configure Network → Set Hostname (e.g., kali).

Set root password.

Disk Partitioning: Use entire disk → All files in one partition.

Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

Use root credentials.

8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali
# Snapshots:
AWS Account Creation Snapshot
# Snapshot 1: Installing Oracle VirtualBox image
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4fedc2a7-959f-4545-b4dc-726fd9ae0065" />

# Snapshot 2: Kali or Parrot Running in Virtual image

<img width="1914" height="1022" alt="image" src="https://github.com/user-attachments/assets/85f2a997-c23a-44a1-8610-3dc8a3f07e5e" />

# Result :
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
<img width="1122" height="193" alt="image" src="https://github.com/user-attachments/assets/ab801f56-fc8c-4cc3-a41e-56d9447c1ea6" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="1074" height="90" alt="image" src="https://github.com/user-attachments/assets/db983924-485c-48af-b3bb-6373e057fab5" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
<img width="1118" height="159" alt="image" src="https://github.com/user-attachments/assets/7dc2be4d-44de-4fe0-b3ba-32f7c6c094e3" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
<img width="1117" height="165" alt="image" src="https://github.com/user-attachments/assets/ae721269-a62f-44bd-9989-0d22fbdeb5c4" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
<img width="1080" height="194" alt="image" src="https://github.com/user-attachments/assets/aee80c1d-e4e1-4fa8-a67a-285da3298f86" />

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="1115" height="218" alt="image" src="https://github.com/user-attachments/assets/b148980e-e9fc-497f-80c9-f056e03846ec" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
<img width="1089" height="161" alt="image" src="https://github.com/user-attachments/assets/aa7de482-aa77-427d-b9f9-44f56a81aaa9" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="776" height="61" alt="image" src="https://github.com/user-attachments/assets/bad9465e-fb24-4369-99d1-72279d71198d" />

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="974" height="110" alt="image" src="https://github.com/user-attachments/assets/ab23fe94-c4a3-4c02-9d99-effb6aa81922" />

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

## Result

