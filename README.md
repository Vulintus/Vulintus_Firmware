# Vulintus Firmware Releases
Public repository where users can find firmware updates for Vulintus products.

## Vulintus_Firmware_Updater.exe
To help easily update the firmware on you MotoTrak and OmniTrak Controllers, we've created a simple program called Vulintus Firmware Updater, written and compile in MATLAB. The installer for the Vulintus Firmware Updater can be downloaded with this repository, or from this direct link:

[Vulintus Firmware Updater (2022-02-02)](https://github.com/Vulintus/Vulintus_Firmware_Releases/raw/main/Vulintus_Firmware_Updater_Installer_20220222.exe)

To update your controller firmware, download and install Vulintus_Firmware_Updater.exe, and then launch the program. You will see selection boxes to select a COM port and a HEX/BIN file. If your  controller  isn't plugged in yet, connect it to the computer with the USB cable. Then click the "Scan" button to the right of the COM port box to refresh the list of connected devices. You can plug/unplug and re-scan the devices to figure out which COM port is the carousel, and then select that one in the top box.

Next, download the HEX file that you want to install on your controller from this repository, and then select the file in Vulintus Firmware Updater by clicking the "Load" button.

Finally, for MotoTrak Controllers, set the programmer to "avrdude.exe". For OmniTrak Controllers, set the programmer to "bossac.exe". Then press the PROGRAM button. You'll see some messages about the programming routine and then, if it programs successfully, it should say "Microcode successfully updated!"
