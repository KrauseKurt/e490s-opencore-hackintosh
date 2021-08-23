# e490s-opencore-hackintosh
OpenCore EFI for the ThinkPad e490s, currently in development.

OS Version: Big Sur 11

If you are going to use this for your e490s use at your own risk, i higly suggest you to follow and learn using Dortania opencore guide before just copy-pasting what is here without understanding it.

What Works:
Nvme,
Ethernet,
Keyboard backlight,
Sound,
Hotkeys for sound,
Headphone Jack,
Internal Speakers,
Internal Mic,
Type A USB Ports,
Webcam,
ThinkPad Clickpads,
ThinkPad Pointer,
Screen backlight level,
iGPU

Issues know/being worked on:
Fans go brrrrr,
Built In MicroSD Reader,
Hibernation/Sleep,

Wont work:
Wifi because of Intel Wireless-AC 9260 (no chance it works, Intel Wireless is not supported by Apple),
Battery Life Estimation (macOS doesn't have this feature)

Untested:
Battery Level Status (use RehabMan patch to create your own),
HDMI Video and Audio Output,
SATA drivers,
Bluetooth as well as bluetooth earphones, airpods,
Shows correct battery serial number and cycles,
Type C USB Video Output,

