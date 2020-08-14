title: Android Images
---

<img align="right" src="AndroidImages.assets/Android_logo_2019-1593412753766.png" />

<br>

## Android 10

Boot the system with the SD card placed in the slot located on the carrier, once booted you will see the following screen:

<img src="AndroidImages.assets/Screenshot_20200608-082418.png" alt="Screenshot_20200608-082418" style="zoom: 33%;" />



### Binary Image download Link

* Android 10  (image size: 989 MB - **Beta Release**): [Click here](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-PX30/Images/Android/LEC-PX30-IPI-SMARC_Android10_sdcard_2v4_20200805.zip)

  **Note**:
  
  1. Please refer to [here](https://docs.ipi.wiki/iot_pi/HowToFlashImage.html#To-Flash-the-Yocto-Android-Image) to guide you how to flash image to SD card
  2. Boot selector in I-Pi board won't work due to the design of [PX30 booting procedure](PX30BootFlow.html)

<br>

## Supported features & interfaces 

* Linux Kernel version: **4.19**
* [40 Pin expansion Header](UserInterfaces.html) with UART, I2C, GPIO support 
* Support H.265, H.264, MPEG-4, VP8, and VC-1 video format with up to 1080p60fps
* 2D / 3D Graphics Acceleration [with Arm Mali-G31 GPU](https://developer.arm.com/ip-products/graphics-and-multimedia/mali-gpus/mali-g31-gpu) 
* 4x USB 2.0 ports
* 2x 10/100 Mb LAN ports 
* HDMI output with resolution 1920x1080@60Hz
* Analog to Digital input interface
* Audio & speaker
* USB OTG support ADB Shell
* CAN FD Bus interface
* [MicroG ](https://microg.org/) service support: Providing the functionality required to run apps that use Google Play Services.
* Raspberry Pi Camera V2.1 (2 Lanes) - SONY iMX219 sensor ([Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/))  
* WIFI/BT USB Dongle ([EW-7611ULB datasheet](https://www.edimax.com/edimax/mw/cufiles/files/download/datasheet/EW-7611ULB_datasheet_English.pdf))

<br>

##### Running the 3D benchmark 

![](AndroidImages.assets/benchmark-1594969675942.png)