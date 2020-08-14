title: Yocto Linux Images
---

<img align="right" src="YoctoImages.assets/yocto_project_eebe407216.png" />

<br>


## Yocto Zeus with Xfce Desktop Environment

Boot the system with the SD card placed in the slot located on the carrier, once booted you will see the login screen:

<img src="YoctoImages.assets/yocto_desktop.png" alt="yocto_desktop" style="zoom: 33%;" />

<br>


## Usernames and passwords
* One user is defined on the system: **root**

* password is **adlink123**

  

### Binary Image download Link
* Pre-compiled Yocto Zeus image with XFCE desktop and MRAA/UPM libraries (image size: 1.8GB): [Click here](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-PX30/Images/Yocto/LEC-PX30-IPi-SMARC_Yocto-Zeus-v2.0_SD_20200623.zip)

  **Note:**: 

  1. Auto-login is enabled and no need to enter password     
  2. Please refer to [here](https://docs.ipi.wiki/iot_pi/HowToFlashImage.html#To-Flash-the-Yocto-Android-Image) to guide you how to flash image to SD card
  3. Boot selector in I-Pi board won't work due to the design of [PX30 booting procedure](PX30BootFlow.html)
  
  



## Supported features & interfaces 

* Linux Kernel version: **4.4.185**
* [40 Pin expansion Header](UserInterfaces.html) with [Eclipse Mraa library](https://github.com/eclipse/mraa) and [Eclipse UPM library](https://github.com/eclipse/upm) which supports C/C++, Python, JAVA and JavaScript 
* Support H.265, H.264, VP8 video format with up to 1080p60fps
* 4x USB 2.0 ports
* 2x 10/100 Mb LAN ports
* HDMI output with resolution 1920x1080@60Hz
* CAN FD Bus interface
* Analog to Digital input interface
* Audio & speaker
* Raspberry Pi Camera V2.1 (2 Lanes) - SONY iMX219 sensor ([Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/))
* WIFI/BT USB Dongle ([EW-7611ULB datasheet](https://www.edimax.com/edimax/mw/cufiles/files/download/datasheet/EW-7611ULB_datasheet_English.pdf))

<br>