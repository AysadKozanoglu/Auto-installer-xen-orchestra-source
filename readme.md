# XENSERVER - Xen-Orchestra (Community Edition) Installer
Distribution: debian jessie 8.11 (production tested)
XENSERVER: 6.5 > and above would work fine

Xen-Orchestra (Community Edition) allows you to administer Citrix XenServer and XCP-ng as well as backup any VM's running on these systems. 

The single line installation script allows you to go from a bare-minimal installation of Ubuntu or Debian (Server) to <b><i> fully operational XOCE server. </i></b>

#### INFO  requirements 
##### before running Auto-installer Script:

+ Server pool created over XenCenter Tool
+ Create a VM with XenCenter 
    + 2GB RAM, 10GB vdisk, 1 vCore CPU
+ Install Debian jessie 8.11 Core/ Base / minimal installation


#### Xen Orchestra Community edition - oneline Auto installer script 

Run the following step from a root shell.

```
curl https://git.io/fhIr6 | bash
```

wait the installation sequenz on CLI finishing.


#### screenshot

##### Auto-installer Finished Status:
![xen orchestra auto installer](https://raw.githubusercontent.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/master/xen-orchestra-community-autoInstaller.png)

###### Xen Orchestra Community edition GUI
![xen orchestra community edtition GUI](https://github.com/AysadKozanoglu/Auto-installer-xen-orchestra-source/raw/master/xen-orchestra-community-autoInstaller-gui.png)

that's it.
