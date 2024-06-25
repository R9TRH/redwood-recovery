# redwood-recovery
Recovery For Poco X5 Pro AOSP ROMs
# How to install
If you have AOSP-based recovery (Los recovery, Arrow recovery etc.) just sideload. 
command: adb sideload (recovery-name).zip

If you have TWRP/OFOX/etc. that can directly flash zips, just flash.

Download files from 

https://github.com/R9TRH/redwood-recovery/releases/latest

# How to use (Important)
1. Flash the ROM normally. Go to install, select your ROM.zip, and confirm. no need to change any option.
IMPORTANT: Don't flash any zip after ROM. follow steps bellow and reboot recovery then flash zips like GApps, Magisk, etc.


3. Go back to main page, Go to wipe, do format data, and wipe cache from advanced wipe. (For clean flashes only. If you are just updating, ignore this step)


4. Go back to main page, Go to reboot section, and change active slot. If active slot was A, select B. Or if active slot was B, select A. There is an indicator there shows active slot.


5. Go back to main page, go to Advanced, select "flash current TWRP". If you forget this step, you'll lose TWRP after reboot.


# CREDITS
@Telexec for initial version & help 

@osm0sis for build scripts

@TheStrechh for full working TWRP & OFOX
