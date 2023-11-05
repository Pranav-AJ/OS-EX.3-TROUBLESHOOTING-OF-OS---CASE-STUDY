# OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY

## AIM:
To troubleshoot a problem(Audio driver) in an operating system.

## PROCEDURE:
### STEP 1 Run Playing Audio troubleshooter:
 You can treat this tool as first aid solution for the fixing audio problems. This in-built tool can find and fix audio problems automatically.
1. Open Settings app and go to System.
2. Under System, go to Troubleshoot > Other troubleshooters.
3. Click on Run next to Playing Audio troubleshooter.
   
![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/e0134214-9a0e-4810-9230-af3b45af83fe)

In few moments, you will see that Playing Audio troubleshooter has found some problems and fixed them. If troubleshooter found some issues but can't fix them, continue following other methods mentioned next in this guide.

![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/cd64271f-34a2-4b85-833a-3c13e3f32368)

### STEP 2 Fix the audio driver:
In most of cases involving audio problems, audio drivers can be the main root cause. You can try the following suggestions if the audio driver is causing an audio problem on your system:
1. Right-click on the Start button or press Windows + X and select Device Manager.
2. Under Device Manager, expand Sound, video, and game controllers or section where audio devices are listed.
3. Locate your audio device/driver and double-click on it.
4. Verify if the device status is This device is working properly.
   
![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/d6c04b45-5431-47af-b677-e2c5261fbd66)

### STEP 3 Update or roll back your audio driver:
If the audio driver is listed and working properly, but still you don't get your audio issue fixed, next you can try updating your audio driver. Double click on the audio driver, go to Driver tab and click Update driver. Follow on-screen instructions to complete the update.

![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/9b54f2f5-6071-4f64-b95d-0d6bb6bc1740)

### STEP 4 Fix the audio services:
If running a troubleshooter and making changes to the audio driver was of no help, you can next check for audio background services.
1. Press Windows + R, type services.msc and click OK.
2. In the Services window, make sure these services are Running and have their Startup type set to Automatic:
3. Windows Audio
4. Windows Audio Endpoint Builder
5. Remote Procedure Call
   
![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/947b4d1f-9b02-42bc-964a-39c3c2a282f4)

### STEP 5 Disable audio enhancements:
If previous methods were not helpful, then you can try disabling audio enhancements and see if it helps.
1. Go to Settings > System > Sound.
2. Click More sound settings.
3. On Sound tab, select your primary audio device and click Properties.
4. On property sheet, go to Enhancements tab.
5. Check Disable all enhancements.
6. Click Apply, OK.
   
![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/72210dff-565a-4bdc-92e4-df469c4290b8)

If audio is not working on some specific apps, you go to the Advanced tab and uncheck Allow applications to take exclusive control of this device option. Click Apply, OK.

![image](https://github.com/Pranav-AJ/OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY/assets/118904526/4cfd076a-eb8d-4e18-8f54-9876c0eef416)

## RESULT:
Troubleshooting of OS has been done successfuly.
