# platform-banana-pi
Platform files for banana-pi devices

BPI-Sinovoip sources: http://github.com/BPI-SINOVOIP/BPI-M2U-bsp
LeMaker Banana Pi Pro sources: http://github.com/linux-sunxi/linux-sunxi

This repo contains all platform-specific files, used by the Volumio Builder to create **banana-pi** images:

- Kernel (kernel, modules, firmware)
- Other files e.g. u-boot, configuration files, uEnv.txt, boot.cmd, boot.scr etc.

For the BPI_M2U the BSP is used to generate most of the needed components.
A Volumio-specific script can be used to copy out the data to the platform folder and tar it.
The tar is to be used by the Volumio build process.

For the Banana Pi Pro, the instructions from the sunxi wiki were used

**Platform BPI-M2U files with kernel version 3.10.65**
- 20161129: First commit for Volumio 2

** Waiting for more documentation on bpi-m2u, currently initrd does not load **  

**Platform BPI-PRO files with kernel version 3.4.10**
- 20170113: First commit for Volumio 2, standard linux-sunxi kernel, patched with overlayfs



