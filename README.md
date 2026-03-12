## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: Naveen R
## REG NUMBER: 212224110040
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

- Visit Oracle VirtualBox Official Site
- Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

- Launch Installer → Allow Changes → Click Next.
- Choose Installation Options → Click Next.
- Accept Network Interface Warning → Click Yes.
- Click Install.
- Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

- Open VirtualBox.
- Click New → Name VM → Select Type (Linux/Windows) and Version.
- Allocate:
  
     Minimum 2 GB RAM
  
     Create Virtual Hard Disk (20 GB recommended).
  
- Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image
## Steps:

1.Download Kali Linux ISO:
- Visit Kali Linux Official Site
- Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:
- Open VirtualBox → Click New.
- Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
- Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:
- Select VDI (VirtualBox Disk Image).
- Choose Dynamically allocated.
- Set Disk size to 20 GB or more.
  
5.Configure ISO Image:
- Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:
- Boot Virtual Machine → Choose Graphical Install.
- Set Language, Region, Keyboard.
- Configure Network → Set Hostname (e.g., kali).
- Set root password.
- Disk Partitioning: Use entire disk → All files in one partition.
- Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:
- Use root credentials.
  
8.(Optional) Install Guest Additions:
- Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot
## Snapshot 1: Installing Oracle VirtualBox image
<img width="927" height="497" alt="Screenshot 2025-08-28 103507" src="https://github.com/user-attachments/assets/80010f1b-318d-437f-962c-a741cfda0d3d" />


## Snapshot 2: Kali Running in Virtual image
<img width="935" height="573" alt="Screenshot 2025-08-28 103519" src="https://github.com/user-attachments/assets/4894b551-1dc5-4ffd-8354-eadb514f50ba" />


## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="855" height="68" alt="cs1" src="https://github.com/user-attachments/assets/f2f46d3b-604e-4c5c-8229-c7ca373282c2" />


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="250" height="67" alt="cs2" src="https://github.com/user-attachments/assets/ed6c9de2-037f-4c56-bb03-b81df8c0241b" />


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="930" height="116" alt="cs3" src="https://github.com/user-attachments/assets/11912044-da1b-4871-8437-23e2bfe86dfb" />


## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="888" height="127" alt="cs4" src="https://github.com/user-attachments/assets/1d3dabb8-df45-48c7-84f8-23dfc91e86d1" />


## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="354" height="158" alt="cs5" src="https://github.com/user-attachments/assets/ab7062f1-24ad-4e23-9460-fd2f937e7b51" />


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="350" height="183" alt="cs6" src="https://github.com/user-attachments/assets/367c2256-e65c-4251-94b4-968e150a1f24" />


## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="334" height="133" alt="cs7" src="https://github.com/user-attachments/assets/7437249d-aaa5-430e-a242-c2037f9cf381" />


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="501" height="40" alt="cs8" src="https://github.com/user-attachments/assets/aea7bca5-5c26-46bb-a180-986681a80e14" />


## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="296" height="88" alt="cs9" src="https://github.com/user-attachments/assets/7ac4ef75-ca8e-4d35-8d53-0aaee9637d26" />


## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="363" height="265" alt="cs10" src="https://github.com/user-attachments/assets/82dfea24-c76b-4f78-ba13-62c8b1322160" />


## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="462" height="171" alt="cs11" src="https://github.com/user-attachments/assets/926c9950-4260-437d-bb81-040c3a7670bb" />


## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="394" height="528" alt="cs12" src="https://github.com/user-attachments/assets/73a75ddb-cb76-4f6d-b59c-6779272f29a0" />


## 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="299" height="238" alt="cs13" src="https://github.com/user-attachments/assets/ffa8c88c-2c50-4702-a28e-2a26f2dd6129" />


## 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="931" height="48" alt="cs14" src="https://github.com/user-attachments/assets/7ad8c195-85aa-48c2-ab75-47ede32cd166" />


## 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="349" height="74" alt="cs15" src="https://github.com/user-attachments/assets/74349097-1bc3-4e9c-a004-a5912c99b017" />


## 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="465" height="299" alt="cs16" src="https://github.com/user-attachments/assets/10c9eb2b-157d-4206-a9df-dfa870a4ff12" />


## 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

<img width="450" height="118" alt="cs17" src="https://github.com/user-attachments/assets/05aecff4-d510-421b-827b-3236038e3e5c" />


## 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="369" height="159" alt="cs18" src="https://github.com/user-attachments/assets/e921e18d-2e0a-4cf5-a4d1-b397f6e44ecf" />


## 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="472" height="132" alt="cs19" src="https://github.com/user-attachments/assets/62eedfd2-715a-4da5-b056-4131a132aed5" />


## 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="233" height="67" alt="cs20" src="https://github.com/user-attachments/assets/fb212213-9e76-43fd-8260-f5b510731dda" />


## 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="861" height="104" alt="cs21" src="https://github.com/user-attachments/assets/e31638d9-d5da-43dd-b65e-ad271833d602" />


## 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="493" height="118" alt="cs22" src="https://github.com/user-attachments/assets/8ad5d3d6-29f6-4923-a724-9f8faa729750" />


## 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="605" height="101" alt="cs23" src="https://github.com/user-attachments/assets/16c4a668-9c91-49cd-8f5b-5fb84f3da6da" />


## 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

<img width="926" height="148" alt="cs24" src="https://github.com/user-attachments/assets/92b7b483-82aa-4837-a445-d2a31d323284" />


## 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="246" height="303" alt="cs25" src="https://github.com/user-attachments/assets/6a91d4c3-1f83-40e6-b63a-573dfea93c16" />


## 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="515" height="294" alt="image" src="https://github.com/user-attachments/assets/b4f0c030-9987-45f5-8e16-aedee1238ddd" />


## 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/5055c031-901e-495e-aa00-a7526c5431d9" />


<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/8c505f70-087d-4953-a335-a07cb59e39c1" />



## 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="743" height="67" alt="cs28" src="https://github.com/user-attachments/assets/dea2e191-62cf-469a-bc7b-cd59b3c10805" />


## 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="930" height="298" alt="cs29" src="https://github.com/user-attachments/assets/9b910c54-e255-4793-b44e-1bde1e5fcbe4" />


## 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="293" height="85" alt="cs30a" src="https://github.com/user-attachments/assets/c8f8528f-ae3b-4756-b934-25eb2f8e6214" />

<img width="351" height="75" alt="cs30b" src="https://github.com/user-attachments/assets/dca642e7-e848-4da3-a6e7-03b51b731bd2" />

## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.

