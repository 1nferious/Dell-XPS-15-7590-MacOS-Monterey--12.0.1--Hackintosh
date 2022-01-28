# Introduction
This is a repository which contains my Hackintosh EFI config using OpenCore bootloader. It's speifically designed for my Dell XPS 15 7590 4K Touch laptop, however may work with other variations of Dell XPS 15 with some minor tweaks and adjustment. It supports MacOS Monterey 12.0.1 and can be upgraded OTA (System Preferences) to 12.2; The current wireless card does support WLAN and Bluetooth, however AirDrop is not supported. MacOS gestures work fine. I don't know about the battery satistics though I can definitely take a look whenever I get the time. Hopefully this helps :)


<img src="https://github.com/1nferious/Dell-XPS-15-7590-MacOS-Monterey--12.0.1--Hackintosh/blob/main/assets/proof.png">


# Tested Configuration
##  Hardware

* Model: Dell XPS 15 7590 4K Touch
* CPU: Intel Core i7
* Intel Graphic: Intel UHD Graphics 630 1536 MB 
* Memory: 32 GB 2667 MHz DDR4
* Display: 4K Touch Screen
* SSD: WD_BLACK:tm: SN750 NVMe:tm: (500 GB)
* WLAN + Bluetooth: Killer Wireless 1650

## Software
* macOS Monterey: `12.0.1` (I later upgraded to Monterey 12.2 through System Preferences)

# What Works
- [x] Wifi
- [x] FaceTime
- [x] iMessage
- [x] Handoff
- [x] Siri
- [x] iCloud
- [x] Find My Mac
- [x] App Store
- [x] Trackpad Gestures
- [x] Keyboard Shortcuts (Volume, Brightness, Play/Pause, Backlight, Print) *FN key needed*
- [x] HDMI Port (4k@30Hz hot pluggable)
- [x] Headphone Jack

# What Doesn't Work :(
- [ ] Airdrop (I have the Killer Wireless 1650. It will work if you have DW1820 or DW1830)
- [ ] Nvidia Geforce GTX 1650
- [ ] 4K Touch Screen
- [ ] SD Card Reader (external USB ones work fine)


# Known Bugs/Issues
* When booting the Boot loader is kind of laggy
