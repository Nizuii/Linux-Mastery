# Linux File System Hierarchy.

<img src="https://cdn.services-k8s.prod.aws.htb.systems/content/modules/18/NEW_filesystem.png">

**/**: The top-level directory is the root file system. It contains all the files required to boot the OS before other file systems are mounted, as well as the files required to boot the other file system. After boot, all of the other filesystems are mounted at standard mount points as subdirectories of the root.  
**/bin**: Contains essential command binaries.  
**/boot**: Consists of static bootloader, Kernel executables, and files required to boot the linux OS.  
