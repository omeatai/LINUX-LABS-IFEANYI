# LINUX-LABS-IFEANYI
by Ifeanyi Omeata

<details>
  <summary>1 - Linux Installation </summary>

  ###

  <a href="" target="_blank"><img src="https://github.com/user-attachments/assets/9b21d709-8705-42ee-bec8-38a7bd09f372" width="720" height="400" /></a>
  
  ### 1. Popular Distributions

  - [ ] [Linux DistroWatch](https://distrowatch.com/)
  #### Fedora-Based
  - [ ] [Fedora](https://distrowatch.com/table.php?distribution=fedora)
  - [ ] [Red Hat Enterprise Linux](https://distrowatch.com/table.php?distribution=redhat)
  - [ ] [CentOS](https://distrowatch.com/table.php?distribution=centos)
  - [ ] [AlmaLinux OS](https://distrowatch.com/table.php?distribution=alma)
  - [ ] [Rocky Linux](https://distrowatch.com/table.php?distribution=rocky)
  #### Debian-Based
  - [ ] [Debian](https://distrowatch.com/table.php?distribution=debian)
  - [ ] [Ubuntu](https://distrowatch.com/table.php?distribution=ubuntu)
  - [ ] [Linux Mint](https://distrowatch.com/table.php?distribution=mint)
  - [ ] [Pop!_OS](https://distrowatch.com/table.php?distribution=popos)
  - [ ] [Kali Linux](https://distrowatch.com/table.php?distribution=kali)
  #### Arch-Based
  - [ ] [Arch Linux](https://distrowatch.com/table.php?distribution=arch)
  - [ ] [Manjaro Linux](https://distrowatch.com/table.php?distribution=manjaro)
  - [ ] [CachyOS](https://distrowatch.com/table.php?distribution=cachyos)
  - [ ] [EndeavourOS](https://distrowatch.com/table.php?distribution=endeavour)
  
  ### 2. Install Linux (Ubuntu) on Windows with WSL
  - [ ] Open Windows Terminal as Administrator
  ```
  wsl --install
  ```

  ### 3. Show all available Linux Distributions we can download to WSL
  ```
  wsl -l -o
  ```

  ### 4. To Install a distribution: debian to WSL
  ```
  wsl --install -d Debian
  ```

  ### 5. To UnInstall a Distro in WSL
  ```
  wsl --unregister Debian
  ```

</details>

<details>
  <summary>2 - Linux Directory Structure </summary>

  ###

  ### Common Directories

  - [ ] / = The directory called "root." It is the starting point for the file system hierarchy. Note that this is not related to the root, or superuser, account.
  - [ ] /bin = Binaries and other executable programs.
  - [ ] /etc = System configuration files.
  - [ ] /home = Home directories.
  - [ ] /opt = Optional or third party software.
  - [ ] /tmp = Temporary space, typically cleared on reboot.
  - [ ] /usr = User related programs.
  - [ ] /var = Variable data, most notably log files.

  ### Comprehensive Directory Listing

  - [ ] /  = The directory called "root." It is the starting point for the file system hierarchy. Note that this is not related to the root, or superuser, account.
  - [ ] /bin  = Binaries and other executable programs.
  - [ ] /boot  = Files needed to boot the operating system.
  - [ ] /cdrom  = Mount point for CD-ROMs.
  - [ ] /cgroup  = Control Groups hierarchy.
  - [ ] /dev  = Device files, typically controlled by the operating system and the system administrators.
  - [ ] /etc  = System configuration files.
  - [ ] /export  = Shared file systems. Most commonly found on Solaris systems./home Home directories.
  - [ ] /lib  = System Libraries.
  - [ ] /lib64  = System Libraries, 64 bit.
  - [ ] /lost+found  = Used by the file system to store recovered files after a file system check has been performed.
  - [ ] /media =  Used to mount removable media like CD-ROMs.
  - [ ] /mnt =  Used to mount external file systems.
  - [ ] /opt  = Optional or third party software.
  - [ ] /proc  = Provides information about running processes.
  - [ ] /root  = The home directory for the root account.
  - [ ] /sbin  = System administration binaries.
  - [ ] /selinux  = Used to display information about SELinux.
  - [ ] /srv =  Contains data which is served by the system.
  - [ ] /srv/www  = Web server files.
  - [ ] /srv/ftp  = FTP files.
  - [ ] /sys  = Used to display and sometimes configure the devices and busses known to the Linux kernel.
  - [ ] /tmp  = Temporary space, typically cleared on reboot. This directory can be used by the OS and users alike.
  - [ ] /usr  = User related programs, libraries, and documentation. The sub-directories in /usr relate to those described above and below.
  - [ ] /usr/bin  = Binaries and other executable programs.
  - [ ] /usr/lib  = Libraries.
  - [ ] /usr/local  = Locally installed software that is not part of the base operating system.
  - [ ] /usr/sbin  = System administration binaries.
  - [ ] /var = Variable data, most notably log files.
  - [ ] /var/log  = Log files

  ### Unix Specified Directories

  - [ ] /devices  = Device files, typically controlled by the operating system and the system administrators.
  - [ ] /kernel  = Kernel and kernel modules. (Solaris)
  - [ ] /platform  = Platform specific files. (Solaris)
  - [ ] /rpool  = ZFS root pool directory. (Solaris)
  - [ ] /net  = Used to mount external file systems. (HP-UX)
  - [ ] /nfs4  = Used to mount the Federated File System domain root. (Solaris)
  - [ ] /stand  = Files needed to boot HP-UX.

  ### Application Directory Structures
  
  - [ ] /usr/local/apache/bin  = The application's binaries and other executable programs.
  - [ ] /usr/local/apache/etc  = Configuration files for the application.
  - [ ] /usr/local/apache/lib  = Application libraries.
  - [ ] /usr/local/apache/logs  = Application log files
  - [ ] /opt/apache/bin  = The application's binaries and other executable programs.
  - [ ] /opt/apache/etc  = Configuration files for the application.
  - [ ] /opt/apache/lib  = Application libraries.
  - [ ] /opt/apache/logs  = Application log files
  - [ ] /etc/opt/apache  = Configuration files for the application.
  - [ ] /opt/apache/bin  = The application's binaries and other executable programs.
  - [ ] /opt/apache/lib = Application libraries.
  - [ ] /var/opt/apache  = Application log files.
  - [ ] /opt/acme  = Company top level directory.
  - [ ] /opt/acme/bin  = Binary programs created by or installed by the Acme Corporation.
  - [ ] /opt/acme  = Company top level directory./opt/acme/apache The top level directory for Acme's installation of apache.
  - [ ] /opt/acme/apache/bin  = The apache binary programs
  - [ ] /opt/web-team  = The web support team's top level directory.
  - [ ] /opt/acme/web-team  = The web support team's top level directory.
  - [ ] /usr/local/acme/web-team  = The web support team's top level directory.
  
</details>






