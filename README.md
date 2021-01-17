LDM info
==========================
ldminfo 

##### 2020-01-16 

Code updated to compile and work on x86_64 Linux and Cygwin 
tested on 2TB drives and test images from libldm
see: https://github.com/mdbooth/libldm/blob/master/test/data/ldm-data.tar.xz


The LDM driver is in the kernel and not included here

The kernel LDM driver prints some warnings on certain dyanmic (LDM) disks
The errors may be safe to ignore and hopefully ldminfo can help troubleshoot.

I am not an expert in LDM disks but these tools have help with troubleshooting 
Windows dynamic disks. 


ldmutil is another utility and includes a utility for creating sparse LDM disk images 
https://github.com/jpmorrison/ldm  (forked from flatcap)




John Paul 

ldm@bogomips.com

