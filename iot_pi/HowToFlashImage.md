title: How to Flash an Image to the SD Card
---

The procedure describes how to flash an **Ubuntu/Debian/Yocto** image including u-boot, Linux kernel and filesystem to the SD Card.



<br>

## To Flash the Ubuntu/Debian Image

### Prerequisites

- Download the prebuilt bootable Ubuntu image to the working directory on your development host.
- In Windows environments, please download [rufus](https://rufus.ie/) to flash the image to the SD Card.

​       **Note:** All files will be erased on the SD Card. The size should be preferable 16 GB or larger. For better performance an class 10 SD card or higher is advised.

<br>

### Windows Host:

1. Insert an empty MicroSD Card into the development host and execute rufus.exe as the picture below. It will auto-detected your storage drives.

<img align="center" src="HowToFlashImage.assets/rufus_1.png" style="zoom: 67%;" />



2. Press the **SELECT** button and browse to the .img file previously copied to your working directory on the development host. Then click **START** and wait for the process to be finished.

<img align="center" src="HowToFlashImage.assets/rufus_2.png" alt="win32diskimager_load_image" style="zoom: 67%;" />




### Linux Host:

1. Copy the prebuilt bootable Ubuntu image to the working directory on your development host. Insert an empty SD Card into the development host and enter the following command to copy the .img to the SD Card.
   
   ```
   $ sudo dd if=[your image].img of=/dev/sd[x]
   ```
   
   **Warning**: Make sure the SD Card device is properly identified as /dev/sdb or /dev/sda  and verify that the device name is correct. Data loss may result if written to the wrong device. 
   
2. After it is completed, please enter the following command:

   ```
   $ sync
   ```



<br>



## To Flash the Yocto/Android Image

### Prerequisites

- Copy the prebuilt bootable Yocto image to the working directory on your development host.
- In Windows environments, please download the [Rockchip SD Firmware tool](https://hq0epm0west0us0storage.blob.core.windows.net/development/LEC-PX30/Tools/SDDiskTool_v1.6.rar) to flash the image to the SD Card.

​       **Note:** All files will be erased on the SD Card. The size should be preferable 16 GB or larger. For better performance an class 10 SD card or higher is advised.


<br>

### Windows Host:

Insert an empty MicroSD Card into the development host and execute the Rockchip SD Firmware tool. 

* Run **SD Firmware Tool**  as an administrator

* Select "Choose removable disk" as your SD card

* Choose "Function mode" as **SD Boot**

* Load your build Yocto image as "Firmware" 

then, click the **Create** button to start the process.

<img src="HowToFlashImage.assets/image-20200303115215481.png" alt="image-20200303115215481" style="zoom:80%;" />

* The tool will prompt to the user that data will be lost. Select "Yes" to continue

* Once done, click **OK** and close the SD Firmware Tool 

* Eject the SD card and insert it into the LEC-PX30 board and power on the board to boot up.


**Note**: There is no need to configure the boot selector of the **LEC-PX30 with Industrial-Pi** for booting from the SD Card. You can directly insert the SD card and power on the system.

