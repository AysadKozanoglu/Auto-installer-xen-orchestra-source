# XENSERVER - Xen-Orchestra (Community Edition) Installer

## [Howto Wiki](https://github.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/wiki)

https://github.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/wiki

### [youtube howto Demo](https://youtu.be/YOXNepl3XUU)


##### Description:

Xen-Orchestra (Community Edition) allows you to administer Citrix XenServer and XCP-ng as well as backup any VM's running on these systems. 

The single line installation script allows you to go from a bare-minimal installation of Ubuntu or Debian (Server) to <b><i> fully operational XOCE server. </i></b>

#### INFO - Requirements:
##### before running Auto-installer Script:

+ XENSERVER: 6.5 > and above would work fine
+ Server pool created over XenCenter Tool
+ Create a VM with XenCenter 
    + 2GB RAM, 10GB vdisk, 1 vCore CPU
    + Install Debian jessie 8.11 Core/ Base / minimal installation


#### Auto Installation Script - Xen Orchestra Community edition from source
oneline Auto installer script 

Run the following step from a root shell.

```
wget -O -  https://git.io/fhIr6 | bash
```

wait the installation sequenz on CLI finishing.


#### screenshot

##### Auto-installer Finished Status:
![xen orchestra auto installer](https://raw.githubusercontent.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/master/xen-orchestra-community-autoInstaller.png)

###### Xen Orchestra Community edition GUI
![xen orchestra community edtition GUI](https://github.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/raw/master/xen-orchestra-community-autoInstaller-gui.png)

that's it.
