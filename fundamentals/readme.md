# Fundamentals

The assumption here is that you have an FV-1 development board

## Running SpinASM IDE on a Mac

The SpinASM IDE (integrated development environment) used to program the EEProm chips is a windows executable - you can see from comments in the thread below that the best way to run it on a Mac is using a windows virtual machine

http://spinsemi.com/forum/viewtopic.php?t=777

This is how I run it - works fine : [Virtualbox](https://www.virtualbox.org/wiki/Downloads) and [Windows 10](https://www.microsoft.com/en-us/software-download/windows10ISO)

Don't forget to add a shared folder, and install the Guest Additions.

### Point your SpinASM IDE at your shared folders

- add to quick view
- create folders in your mac finder or windows file manager
- update each folder
- probably add your shared folder to github

## Connecting your FV-1 to your windows machine

Make sure you connect the FV-1 to your laptop, you should see the status bar update to show the FV-1 is 'online'.

![](../images/StatusBarOnline.png)

If the FV-1 is not connected,  the `devices` menu on the top menu bar

![](../images/DevicesMenu.png)

![](../images/DevicesMenuOpen.png)

Then select the `USB` menu item, where you will probably see a number of well-named devices and one that is called `Unknown Device` - this is your FV-1, click on it to allow the virtual machine connect to it.

![](../images/DevicesMenuOpenUnknownDevice.png)

## Loading a program onto the FV-1

