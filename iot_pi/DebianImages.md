title: Debian Image
---


 <img align="right" src="DebianImages.assets/debian-logo.jpg" width ="150"/>

### Debian 10 Buster with Xfce Desktop Environment

Boot the system with the SD card placed in the slot located on the carrier, once booted you will see the login screen.

<img src="DebianImages.assets/Screenshot_2020-04-23_07-31-23-1587627343117.png" alt="Screenshot_2020-04-23_07-31-23" style="zoom: 33%;" />

​       **Note:** The kernel used is not Debian native. Debian rootfs image which is bootstrapped by the PX30 u-boot & Kernel.



<br>

### Usernames and passwords

   * Two users are defined for use on the system: **px30** and **root**.
   * Passwords is **adlink123** for two users.

<br>

### Binary Image download Link

* Debian 10 Buster image with XFCE desktop and MRAA/UPM libraries (image size: 7.4 GB): [click here](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-PX30/Images/Debian/LEC-PX30-IPi-SMARC_Debian10_xfce_2v2_20200722.zip)

  
  
  **Note**: 
  
  1. Auto-login is enabled and no need to enter password   
  2. Please refer to [here](https://docs.ipi.wiki/iot_pi/HowToFlashImage.html#To-Flash-the-Ubuntu-Debian-Image) to guide you how to flash image to SD card
  3. Boot selector in I-Pi board won't work due to the design of [PX30 booting procedure](PX30BootFlow.html)





<br>

### Supported features & interfaces 

* Linux Kernel version: **4.4.167**
* [40 Pin expansion Header](UserInterfaces.html) with [Eclipse Mraa library](https://github.com/eclipse/mraa) and [Eclipse UPM library](https://github.com/eclipse/upm) which supports C/C++, Python, JAVA and JavaScript 
* 2D / 3D Graphics Acceleration [with Arm Mali-G31 GPU](https://developer.arm.com/ip-products/graphics-and-multimedia/mali-gpus/mali-g31-gpu) which supports x11 display server
* Support H.265, H.264, VP8 video format with up to 1080p60fps
* 4x USB 2.0  ports
* 2x  10/100 Mb LAN ports 
* HDMI output with the resolution up to 1920x1080@60Hz
* CAN FD Bus interface
* Analog to Digital input interface
* Audio & speaker
* Raspberry Pi Camera V2.1 (2 Lanes) - SONY iMX219 sensor ([Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/))  
* WIFI/BT USB Dongle ([EW-7611ULB datasheet](https://www.edimax.com/edimax/mw/cufiles/files/download/datasheet/EW-7611ULB_datasheet_English.pdf))

 <br>

##### Running glmark2-es2 program to benchmark for Mali-G31 with x11

<img src="DebianImages.assets/glmark2_debian.png" alt="glmark2_debian" style="zoom: 40%;" />

