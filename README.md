# RetrOrangePi 4.0 

As expected by the vast majority of users, ROPi 3.0.1 to 4.0 update will work by script, without the need of reflashing your sdcard all over again. We hope this version to be more user-friendly and easily upgradable. 

## Update instructions :
 
- Quit to terminal (from EmulationStation start menu or simply by pressing F4).
- Download the updater: wget http://www.retrorangepi.org/ropi4.sh
- Give it execute permission: sudo chmod +x ropi4.sh
- Run it: sudo -u pi ./ropi4.sh
 
## NOTES:
- Make sure you have 1GB of free space, before running the update. Script will remove update files after completion , so don’t worry.
- It’s possible to update from SSH. Please log with user pi , not root (ever) 
- If all goes well, you should get a confirmation at the end asking you to reboot your board.

## this RetrOrangePi repository features
- An EmulationStation RetroPie platform submenu
- Multiboot environment (runs from Armbian Desktop, available from ES soon)
- AV switcher with overscan fix (HDMI 720p, NTSC/PAL analog)
- eMMC installation tool (sdcard slot will still be alive after reboot)
- ROPi Wifi (a simple NMTUI run script, running from Desktop is recommended)
- ROPi Radio (retrogaming music streams from the web)
- Background music (add your own to ~/RetroPie/music)
- ROPi updater (new features, enhancements and tweaks weekly, translations to MANY languages in the works will come next.)
- Curvature shader + console overlays (for Libretro cores, press Select + X and use options from menu, overlay display and quick menu - shaders)

There are plenty of Retroarch customizations, like the unified retroarch.cfg, to make system-wide changes easier. You can still make custom changes in specific platforms/games by using the quick menu within game (Select + X) and the options Save Core/Game Overrides. Retroarch menu now works very smooth.

## Multiboot environment

ROPi 4.0 will firstly boot to EmulationStation; map your controller. You can open the Armbian Desktop and switch to your preferred boot-type (EmulationStation, AdvanceMENU, Retroarch, Kodi or Desktop)

### EmulationStation

The classic RetroPie frontend, features background music, custom ROPi theme and exclusive menu options (inside Retropie section).

### Retroarch

Libretro's own frontend/emulator, Retroarch is the heart of the emulation component. This option will get you a similar build of Lakka. (XMB menu driver) 

### Kodi

Boots to our Kodi Krypton 17.4 build, with hardware acceleration powered by MPV player and VDPAU. IPTVSimple is included; enable it from the addons menu.

### Desktop

Classic Armbian Desktop version, with several pre-installed applications. Includes onscreen keyboard, so you just need a mouse. 

### AdvanceMENU

MAME versatile frontend, supports picture and video snapshots. Reads roms from mame-advmame folder. Full integration with RetroPie platforms is possible and will be added soon (keyboard recommended).


* Download site: http://www.retrorangepi.org/
* Forum: http://orangepi.club/forumdisplay.php?fid=31
* Facebook page: https://www.facebook.com/retrorangepi/
* Facebook group: (https://www.facebook.com/groups/1131759626884432/



