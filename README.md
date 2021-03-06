# OS X Patcher
OS X Patcher is a command line tool for running OS X Mountain Lion, OS X Mavericks, OS X Yosemite, and OS X El Capitan on unsupported Macs

# Supported Macs

## MacBooks
- MacBook2,1
- MacBook3,1
- MacBook4,1

## MacBook Airs
- MacBookAir1,1

## MacBook Pros
- MacBookPro2,1
- MacBookPro2,2

## iMacs
- iMac4,1
- iMac4,2
- iMac5,1
- iMac5,2

## Mac minis
- Macmini1,1
- Macmini2,1

## Mac Pros
- MacPro1,1
- MacPro2,1

## Xserves
- Xserve1,1
- Xserve2,1

# Brightness Slider and NoSleep

You might notice two little applications have been installed along with OS X Patcher's other patches. They help solve some issues and should be opened and configured after patching. NoSleep is open source and can be found on GitHub. Brightness Slider is made by ACT Productions and can be found on the Mac App Store.

# Graphics acceleration

Your Mac won't support graphics acceleration with this patcher. This means brightness control and sleep won't work (on non-ATI cards) (see above) and applications that rely on your graphics card will perform slower or will simply not work.

# Usage

## Create Installer Drive

### Step 1

Download the latest version of the patcher from the GitHub releases page.

### Step 2

Open Disk Utility and select your installer drive, then click Erase.

### Step 3

Select Mac OS Extended Journaled and click Erase.

### Step 4

Unzip the download and open Terminal. Type chmod +x and drag the script file to Terminal, then hit enter. Then type sudo, drag the script file to Terminal, and hit enter.

### Step 5

Drag your installer app to Terminal. Then select your installer drive from the list and copy and paste the number.

## Erase System Drive

These Steps are optional. A clean install is recommended but not required. It's recommended to make a Time Machine backup before erasing your system drive.

### Step 1

Open the Utilities menu and click Disk Utility. Select your system drive and click Erase.

### Step 2

Select Mac OS Extended Journaled and click Erase.

## Install the OS

### Step 1

Boot from your installer drive by holding down the option key when booting and selecting your installer drive from the menu. Then select your language from the list.

### Step 2

Close Disk Utility if you used it to erase your system drive, then click Continue.

### Step 3

Select your system drive, the drive to install the OS on, and click Continue.

Wait 35-45 minutes and click Reboot when the installation is complete. Then boot into your installer drive using the previous instructions.

## Patch the OS

This is the important part. This is the part where you install the patcher files onto your system. If you miss this part or forget it then your system won't boot.

### Step 1

Open the Utilities menu and click Terminal. Type patch and hit enter. Make sure to select the model your drive will be used with. Then select your system drive from the list and copy and paste the number.

Wait 5-10 minutes and reboot when the patch tool has finished patching your system drive. Then boot into your system drive and setup the OS.

## Restore the OS

If you've switched to a new Mac or just want to remove the patcher files from your system, you can run the restore tool from your installer drive.

### Step 1

Boot from your installer drive by holding down the option key when booting and selecting your installer drive from the menu. Then select your language from the list.

### Step 2

Open the Utilities menu and click Terminal. Type restore and hit enter. Make sure to select the model you selected when you last patched. Then select your system drive from the list and copy and paste the number.

Wait 5-10 minutes, then reinstall the OS.