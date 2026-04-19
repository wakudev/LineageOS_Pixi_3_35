# LineageOS_Pixi_3_35
This repository contains my fully functional custom ROM for the Alcatel OneTouch Pixi 3 (the 3.5-inch model).

MADE IN ARGENTINA WITH LOVE FOR THE COMMUNITY <3

LineageOS 14.1 (Based on Android 7.1.2 Nougat)
Works on Single-SIM models (OT-4009A/F)

Working Features:
Wi-Fi
Bluetooth
Sound
AudioFX
Vibration
LCD Backlight
Mobile Networks (3G/2G)
Graphics Acceleration
MicroSD Cards
Wi-Fi Hotspot and USB Tethering
Root Access
Alarms
Flashlight
Physical Navigation Buttons (Back, Home, and Options)
Offline Charging

Not Working Features:
FM Radio
CM Profiles (Does not affect general use)
SELinux Enforcing

Includes:
F-Droid
Aurora Store
Simple Keyboard
Via Browser

Optimizations, Aggressively optimized to avoid crashing on its meager 512MB, these cuts were made:
Only 3 apps maximum in the background
Reduced logs to prevent excessive CPU usage
Does not include Google apps or services; it was also configured to avoid errors caused by the absence of Google Mobile Services (GMS)
Includes the basics such as Phone, Contacts, SMS, Camera and Gallery, Calculator, and Settings.

Common Bugs, These are not my errors but errors inherent to Lineage (formerly CyanogenMod):
Permissions for downloaded apps must be manually enabled or the app must be restarted after granting permission
Occasionally, Wi-Fi tends to be unreliable if the connection is too far away
The Welcome Assistant cannot be disabled, so it's best to skip everything and configure it later.

Requirements:
TWRP 3.X
Charge it to at least 50% (it usually takes a while)
