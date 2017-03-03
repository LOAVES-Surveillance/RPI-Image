#RaspberryPi-Image
If you are having trouble downloading the LOAVES-Surveillance programs on to your raspberry pi, follow [this link](https://drive.google.com/open?id=0B4w2yS9E929tT21fUU52a2dzbWs) to download the pre-configured SD card image containing everything you need to run the system. Then follow the steps below. The current image is running Raspbian Jessie with Pixel

##Steps for Windows Users
1. Download the image on to your computer.
2. Download and install the free program, Win32 Disk Imager which is found [here](https://sourceforge.net/projects/win32diskimager/).
3. Once installed, start the program and insert the SD card you will be using on your raspberry pi into your computer.
4. While Win32 Disk Imager is open, find the "Image File" text box and put in the location of the image of the raspberry pi that you downloaded.
5. Under "Device", select the SD card that is inserted in your computer.
6. Click the "Write" button. The program will now write the image file to your SD card.
7. Once the writing process has completed, eject your SD card from your computer and insert into your raspberry pi.
8. Start your raspberry pi up.

##Steps for Mac Users
1. Download and install the SD Association's Formatting tools from [here](https://www.sdcard.org/downloads/formatter_4/eula_mac/)
2. Select "Overwrite format"
3. Make sure you have selected your SD Card, and not something else
4. Click "Format"

##Steps for Linux Users
1. Insert your SD card.
2. Format it as FAT32
3. Extract the .img file you downloaded earlier.
4. Copy the file you extracted to your SD card.

If following the above steps was unsuccessful, follow the link [here](http://elinux.org/RPi_Easy_SD_Card_Setup) for further information on how to set up the image file.
