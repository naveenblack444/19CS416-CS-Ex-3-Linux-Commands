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

## Linux Commands
