## Raspberry Pi Deskop Setup

When the Raspberry Pi Desktop VM boots you will be presented with the GNU GRUB boot loader.

![GNU GRUB boot screen](images/debian_boot_screen.png)

+ Select `Debian GNU/Linux` and press Enter to boot Raspberry Pi Desktop.

The Raspberry Pi Desktop will boot in a small VirtualBox window.

![Raspberry Pi Desktop](images/step21.PNG)

### Install VirtualBox Guest Additions

Guest additions will make using your Raspberry Pi Desktop VM much easier by automatically resizing the screen size, enabling copying and pasting between your computer and the VM and sharing folders.

+ Select `Devices` from the VirtualBox menu and then click `Insert Guest Additions CD Image`.

![insert guest additions cd image](images/step22.PNG)

+ Raspbian will confirm that `Removable medium was inserted`, click `Cancel`.

![removable medium inserted](images/step22_5.PNG)

+ Open a Terminal by clicking the Rasperry Pi Desktop menu and selecting `Accessories`, `Terminal`.

![open a terminal](images/using_step16.PNG)

+ Run the guest additions installation program:

```bash
sudo sh /media/cdrom/VBoxLinuxAdditions.run
```

![run guest additions installation](images/step23.PNG)

The installation will run and when finished display the message `VirtualBox Guest Additions: Starting` when complete.

![guest additions installed](images/step24.PNG)

+ When completed reboot your Raspberry Pi Desktop by clicking the menu, selecting `Shutdown` and clicking `Reboot`.
