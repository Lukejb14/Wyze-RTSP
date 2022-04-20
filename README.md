# Wyze RTSP

Download the latest RTSP firmware for Wyze cameras as Wyze.com has removed the downloads from their forums.
> **[Wyze Update](https://support.wyze.com/hc/en-us/articles/360026245231-Wyze-Cam-RTSP) 04/05/2022:** RTSP was considered a beta feature and we are currently assessing the path forward as the firmware versions have aged quite a bit. Wyze has removed the firmware files for these versions for now and will update the pages when plans are finalized. Please note that firmware files take a while to work on and test so you may not see an update in the near future. Wyze apologizes for the inconvenience.

### Highlights
- RTSP Downloads
- How to Install RTSP Firmware
- How to turn on RTSP


### Supported RTSP Cameras

 - [x] Wyze Cam v3
	 - Supports CamPlus but not recommended by Wyze
 - [x] Wyze Cam v2
	 - Supports CamPlus but [special setup required](https://github.com/Lukejb14/Wyze-RTSP/wiki/v2-Cam-Plus-and-RTSP)
 - [x] Wyze Cam Pan v1

# Download RTSP Firmware
- [Wyze Cam v3 Firmware (4.61.0.1 September 2021)](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_wcv3.bin)
	- MD5 Hash:  9a6b59f0c143d7a031adcf27ae52de0a
- [Wyze Cam v2 Firmware (4.28.4.49 November 2020)](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_v2_rtsp_4.28.4.49.bin)
-  [Wyze Cam Pan Firmware (4.29.4.49 March 2021)](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_Pan_rtsp_4.29.4.49.bin)
# How to Install RTSP Firmware

 1. Download the Wyze Cam v2 RTSP file, the Wyze Cam v3 RTSP file, or the Wyze Cam Pan RTSP file. Please note that the Wyze Cam Pan firmware file is **not**  compatible with Wyze Cam Pan v2.
 2. Choose which firmware to install:
	 - For **Wyze Cam v2 and Pan**, unzip the file and rename the contents to '**demo.bin**'. Then transfer the files to a microSD card's root directory.
		 - [Download Wyze Cam v2 Firmware](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_v2_rtsp_4.28.4.49.bin)
		 - [Download Wyze Cam Pan Firmware](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_Pan_rtsp_4.29.4.49.bin)
	 - **For Wyze Cam v3**, transfer the **‘demo_wcv3.bin’** file to a microSD card's root directory
		 - [Download Wyze Cam v3 Firmware](https://github.com/Lukejb14/Wyze-RTSP/blob/main/RTSP_Firmware_Downloads/demo_wcv3.bin)
3. Unplug your Wyze Cam and insert the prepared microSD card ![enter image description here](https://support.wyze.com/hc/article_attachments/360042364711/microSD__1_.png)
4. Hold the camera's **Setup** button while plugging in the USB cable and continue to hold the **Setup** button until the light turns **solid blue** 🔵 for **Wyze Cam v2 and Pan** or **purple** 🟣 for **Wyze Cam v3**.
5. Once the light is solid blue, release the **Setup** button and wait for 3-4 minutes. The camera will reboot, and the status light will change during this time.  
	- _Note: The "Solid Blue" in this case is not the same as the one normally seen on the cameras. It would be lighter and yellowish on Wyze Cam v2 and Pan and purple on Wyze Cam v3._
6. Once this process is finished, you should see the Wyze Cam in your Home tab **without** going through the setup process as long as it was previously paired with your account.

# How to turn on RTSP

1.  Once your Wyze Cam is back online, you can access the RTSP function from the live stream (Wyze app version 2.3 or later) under  **Settings -> Advanced Settings -> RTSP**
2.  The app will automatically check if the installed firmware version is RTSP compatible. If not, please repeat the installation process above.
3.  Next, turn on the  **RTSP toggle**
4.  You'll be prompted to set up a username and password for this Wyze Cam. Both the username and password should be 4 – 10 characters without special characters (only a-z, and 0-9)
    -   PLEASE NOTE - This username and password is unique to just this camera. Please either use something that's easy to remember or take note of them somewhere, as these will be needed to access the camera's stream via RTSP
5.  Click “**Generate URL**”, and the RTSP URL will show on the next screen. Use this for streaming through any RTSP compatible player on the same local network as the Wyze Cam.

_Note: Cam Plus is included on the Wyze Cam v3 RTSP firmware. However, there can be video lag if both functions are streaming video at the same time. We do not recommend running Cam Plus on the RTSP firmware._

---
### Sources
- [WYZE Cam RTSP](https://support.wyze.com/hc/en-us/articles/360026245231-Wyze-Cam-RTSP) 
- WYZE.COM Download links
