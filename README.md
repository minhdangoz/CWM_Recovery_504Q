This is Open Source CWM Recovery of Mobiistar touch LAI 504Q / XOLO Q1000 Opus
Based on CWM Recovery 6.0.3.7



Changelog:

V2: 28/3/2014
- Fix screen rotate 180 degrees issue
- Vietnammese 
- Change background

V1: 20/3/2014
- Fix mount parititions
- Fix graphic color


Guide:
Download source code:

git clone https://github.com/minhdangoz/CWM_Recovery_504Q.git

replace downloaded CWM to /bootable/recovery

- source build/envsetup.sh
- lunch TL504Q
- make -j4 recoveryimage

after making finished use fasbtoot to flash recovery image.
- adb reboot-bootloader //reboot to bootloader mode
- fastboot flash recovery recovery.img //flash new recovery image (CWM)
- fastboot reboot //reboot to Android
- adb reboot recovery //reboot to recovery again
- enjoy !
