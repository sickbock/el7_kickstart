# EL 7 Kickstart
Sample Kickstart configuration(s) for EL 7 (like CentOS 7)

* Files:
  * kickstart-el7-netboot-basic-install.cfg Implements some basic hardening accourding to CIS, requires 10Gb disk
  * minimal_el7.cfg almost no modifications to defaults except for network/hostname
  * minimal_el7_free-space-in-vg.cfg same as above but creates 3Gb root leaving free space in your VG with bigger disk 
* Should prepare the OS for use as a Vagrant basebox
* All logins use the password "vagrant" (see basebox requirements).
