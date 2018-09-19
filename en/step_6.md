## Install Raspberry Pi Desktop

### Start your new Virtual Machine

+ Select your new VM in `Oracle VM VirtualBox Manager`.

+ Click Start.

![start new VM](images/step9.PNG)

+ You will be prompted to select a start up disk, open the Raspberry Pi Desktop iso image you downloaded, by clicking on the folder icon and click `Start`

![select startup disk](images/step10.png)

You VM will now start and the debian install will being.

![debian install startup](images/step11.PNG)

### Install Debian Linux

+ Select `Graphical install` from the Debian GNU/Linux menu.

*If you do not select 'Graphical install' quick enough the installer will start using the default option, if this happens, close the VirtualBox window and click `Start` to restart.*

![debian instal menu](images/step11.PNG)

+ Select your Keyboard type and click `Continue`.

![configure keyboard](images/step12.PNG)

The installation process will now install media and detect what hardware is present.

+ Set how you want to Partition your hard disk, select `Guided - use entire disk` and click `Continue`.

![partition disk](images/step13.PNG)

+ Select the disk to be partitioned, there will be only 1, and click `Continue`.

![select disk](images/step13_5.PNG)

+ Set the partitioning scheme, select `All files in one partition (recommended for new users)` and click `Continue`.

![partioning scheme](images/step14.PNG)

+ Confirm the partition settings by selecting `Finish partitioning and write changes to disk` and clicking `Continue`.

![finish partitioning](images/step15.PNG)

+ Confirm that you wish to write the changes to the disk by selecting `Yes` and clicking `Continue`.

![confirm partitioning](images/step16.PNG)

Debian will now install the operating system.

![debian install](images/step17.PNG)

+ Confirm you want to install the GRUB boot loader on a hard disk by selecting Yes and clicking `Continue`.

![install grub loader](images/step18.PNG)

+ Select the device `/dev/sda` for boot loader installation and click `Continue`.

![select boot loader device](images/step19.PNG)

The installation will now carry on.

+ When installation has finished click `Continue`.

![installation finished](images/step20.PNG)

When installation completes the virtual machine will automatically reboot and you will be presented with the `GNU GRUB boot screen`

![GNU GRUB boot screen](images/debian_boot_screen.png)