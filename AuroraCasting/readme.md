AuroraSystems AuroraCasting
======
- formerly known as OMXconfig
- only works on raspberry pi 3b+ boards
- works with 8+gb micro sd cards, any class
- has templates available on google drive
- relies on OMXplayer, which is deprecated!
- trying to remove the debug screen and boot screen will make the player no longer boot, you have been warned! (yes i wrote a dkms for this, figure out which one!)

Configuration
------
- use the command "omxconfig" to change the systemd service
- then either restart the system, or reload the systemd service
- omxconfig includes a simple automated restart option, that is enabled by default
- AuroraCasting and AuroraSignage come with preset RSA authentication keys, to allow for easier testing, make sure to use your own in prod!
- If you're not using the build script, the default username is root or pi, and the password is: AuraSysmA24
