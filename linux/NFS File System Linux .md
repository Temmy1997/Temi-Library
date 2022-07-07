## NFS (Network File System)
-This is used for sharing files and folders between Linux/Unix systems.
-It helps tp mount local file systema over a network and remote host 
-We can only set up file sharig between UNIX and LINUX.

# BENEFITS OF NFS
-It allows local access to remote files
-It uses standard client/server architecture for file sharing
-it helps to configure centralized storage solutions
-Enabes users to get their data in differnt physical location
-No manual refresh needed for new files


# Important Files for NFS Configuration
/etc/exports : Its a main configuration file of NFS, all exported files and directories are found in this file at the NFS Server end.
/etc/fstab : To mount a NFS directory on your system across the reboots, we need to make an entry in /etc/fstab.
/etc/sysconfig/nfs: Configuration file of NFS to control on which port rpc and other services are listening

