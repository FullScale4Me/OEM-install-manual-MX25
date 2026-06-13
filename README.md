Not all screen options are covered in this manual. 

For furthur guidance see the MX Linux 25 User Manual https://www.mxlinux.org/manuals

OEM Installation

Original Equipment Manufacturer (OEM) is a special installation method that it allows the PC to be shut down just after the Linux OS portion of MX has been installed. Later, a second party boots up that PC and then can resume the MX new user portion of the setup.

This is useful for selling or giving away a computer with an Operating Sysytem pre-installed on it. MX Linux can be installed as an OEM by using a switch in terminal:

sudo minstall --oem

Note: that is two hyphens before oem.

This will install the Operating System only, delaying prompts for user-specific options such as PC name, user name (ID) and password.

Subsequently when booting into this newly installed Operating System for the first time, the user will be asked to provide those details.
