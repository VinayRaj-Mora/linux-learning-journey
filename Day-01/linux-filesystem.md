==Setuping the AWS for linux:
  ==========================
  -> Use EC2 for cloud computing.
  -> Creat SSH key.
  -> Set up the security group.
  
==>>Creating the SSH:
  -> Open the Git bash move to the folder u want to creat the ssh keys (Public and Privet Keys).
  -> In the git bash (ssh-keygen -f "File Name") for ssh key generation .
  -> Connect AWS server with SSH with git bash (ssh -i <private-key> ec2-user@IP).
  -> Lunch the linux server.
 
 
==>Linux Working Directories:
  
  => / -> This is the top-level directory. Every file and folder in Linux starts from.
  => /etc -> Stores system-wide configuration files.
  => /var -> Stores data that changes frequently.
  => /var/lib -> Stores application data.
  => /var/spool -> Stores queued jobs.
  => /home -> Contains personal directories for regular users.
  => /root -> Home directory of the root (administrator) user.
  => /bin -> Contains essential user commands.
  => /sbin -> Contains system administration commands.
  => /usr -> Contains user applications, libraries, and documentation.
  => /boot -> Contains files needed to boot Linux.
  => /dev -> Contains device files.
  => /proc -> A virtual filesystem providing information about the running kernel and processes.
  => /sys -> Another virtual filesystem exposing hardware and kernel information.
  => /tmp -> Temporary files.
  => /opt -> Optional or third-party software.
  => /mnt -> Temporary mount point for manually mounted devices.
  => /media -> Automatically mounted removable media.(USB,DVD ETC).
  => /run -> Stores runtime information created after boot.
  
