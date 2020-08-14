title: Ubuntu Images
---

 ### Ubuntu Bionic 18.04 LTS Xfce Desktop Environment

Boot the system with the SD card placed in the slot located on the carrier, once booted you will see the login screen

<img src="UbuntuImages.assets/Screenshot_2020-01-08_11-51-14.png" alt="Screenshot_2020-01-08_11-51-14" style="zoom: 33%;" />

Ubuntu is not available for download but has to be compiled by the user himself, please follow [the steps](https://ipi.wiki/iot_pi/HowToBuildUbuntu.html) in “build your OS” to do this.

<br />

## Usernames and passwords

* two users are defined on the system: **root**, **adlink**
* password is **adlink123**

<br />

### Binary Image download Link

* Pre-compiled Ubuntu 18.04 LTS image with XFCE desktop and MRAA/UPM libraries (image size: 7 GB): [Click here](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-PX30/Images/Ubuntu/LEC-PX30-iPI-SMARC-Ubuntu-18.04-SDCard-2v1-20200729.zip)

  **Note**: 

  1. Please refer to [here](https://docs.ipi.wiki/iot_pi/HowToFlashImage.html#To-Flash-the-Ubuntu-Debian-Image) to guide you how to flash image to SD card
  2. Boot selector in I-Pi board won't work due to the design of [PX30 booting procedure](PX30BootFlow.html)
  
  <br />

### Supported features & interfaces 

* Linux Kernel version: **4.4.167**
* [40 Pin expansion Header](UserInterfaces.html) with [Eclipse Mraa library](https://github.com/eclipse/mraa) and [Eclipse UPM library](https://github.com/eclipse/upm) which supports C/C++, Python, JAVA and JavaScript 
* 2D / 3D Graphics Acceleration [with Arm Mali-G31 GPU](https://developer.arm.com/ip-products/graphics-and-multimedia/mali-gpus/mali-g31-gpu) which supports x11 display server
* Support H.265, H.264, VP8 video format with up to 1080p60fps
* 4 x USB 2.0 ports
* 2 x 10/100 Mb LAN ports 
* HDMI output with the resolution up to 1920x1080@60Hz
* CAN FD Bus interface
* Analog to Digital input interface
* Audio & speaker
* Raspberry Pi Camera V2.1 with 2 Lanes- SONY iMX219 sensor ([Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/))
* WIFI/BT USB Dongle ([EW-7611ULB datasheet](https://www.edimax.com/edimax/mw/cufiles/files/download/datasheet/EW-7611ULB_datasheet_English.pdf))



<br>

##### Running glmark2-es2 program to benchmark for Mali-G31 with x11

<img src="UbuntuImages.assets/glmark2_ubuntu.png" alt="glmark2_ubuntu" style="zoom:40%;" />





