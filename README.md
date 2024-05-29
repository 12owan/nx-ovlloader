# nx-ovlloader
Host process for loading Switch overlay OVLs (NROs)

This is the loader service of the Tesla ecosystem. It's derrived from the default nx-hbloader.
When being run, this service automatically tries to chainload `/switch/.overlays/ovlmenu.ovl`, the Tesla Menu. From there on it will
load and switch between different overlays on request. 

Same code as the zdm65477730's fork: https://github.com/zdm65477730/nx-ovlloader
Recompiled .zip of the Atmosphere contents and Tesla config.ini included in the files
