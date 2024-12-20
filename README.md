# ARCHforDUMMIES
  It's simply a guide for setting up the Arch Linux distribution for dummies (not Linux begginers!)
  You can follow this guide step-by-step without using your brain or googling stuff. Have fun!

## 1. Bootable USB Drive
  I highly suggest you to use Ventoy for creating bootable thumbdrive. Why? 
  Because you can have MANY .iso files on ONE thumbdrive and switch between different systems.

  To install Ventoy (also supported on Windows) on Linux (i suppose you already have one) you have to download the `tar.gz` file.
  1. Extract Ventoy anywhere you desire
  2. Navigate to its directory and run `./Ventoy-x86_64` (for x86_64 machines) in the terminal.
  3. Select MBR partitioning system (top-left corner), select your USB (usually `/dev/sdc`) and click `Install`
  Congratulations! You made your USB stick bootable. Starting from now, all .iso files you would want to boot from have to be placed in your `VENTOY` directory on your USB thumbdrive.
  If you want to learn more about Ventoy visit [this](https://www.ventoy.net/en/index.html) site.

### Downloading the Arch Linux 
  To download Arch Linux you have to follow these steps:
  1. Move to [Arch Linux Download page](https://archlinux.org/download/) and under the `Worldwide` section choose hosting to download Arch from
  2. Select and download `archlinux-x86_64.iso`
  3. Simply place your .iso file in the previously mentioned `VENTOY` directory of your thumbdrive
  4. Check the hash by moving to .iso location in the thumbdrive and writing `$ sha256sum archlinux-x86_64.iso` in your terminal. The sha256 should match with the one provided on the Arch Linux download site. If not, copy it one more time.
  5. If the sha256 matches, use your Linux GUI to Safely Remove the USB drive (it's important to do not to damage your file
