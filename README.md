# Drivers-FTDI 
Drivers to repair bricked FTDI

These are the original drivers, but have been modified to be installed on bricked devices with PID_0000.

To install the drivers, you must copy them to "C:\Windows\System32\DriverStore\FileRepository"

This drivers has been tested in WIN 8.1/WIN10/Win 11
¡You must restart your PC in "Disable driver signature enforcement" mode:

To disable driver signature enforcement do the following:

1. Press and hold the Shift key on your keyboard and click the Restart button.

![reboot](https://user-images.githubusercontent.com/9281163/184624963-35b2d220-e249-4714-bbfa-2f4dce2cfff0.png)

2. Choose Troubleshoot > Advanced options > Startup Settings and click the Restart button.
3. When your computer restarts you’ll see a list of options. Press F7 on your keyboard to select Disable driver signature enforcement.
![Disable-driver-signature-enforcement](https://user-images.githubusercontent.com/9281163/184624671-f63359a6-ecf4-4780-9f01-fd5008a18eee.png)

Your computer will now restart and you’ll be able to install unsigned drivers.
