# Dell 3100 chromebook root

## Enable developer mode

1. To enable developer mode you need to press `ESC + Refresh + Power` at the same time.

2. Reboot your device and press `CTRL + D` to enable developer mode.

3. Disable OS verification by pressing `CTRL + D` again.

4. Press right alt + t boot chromeOS in developer mode.

## chrome scripts to enable legacy boot

1. Open a terminal (ctrl + a) and type `shell` to enter the shell.

2. Type `sudo crossystem dev_boot_usb=1 dev_boot_legacy=1` to enable legacy boot.

3. Type curl -L -O https://mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh to download and run the script.

4. Select option 3 to install the full ROM firmware.

5. Reboot your device and press `CTRL + L` to boot from USB.

6. Install your favorite linux distro.
