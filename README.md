# remote_pilot
Raspberry-based (wired) remote control sending out Seatalk commands for a Raymarine tiller pilot, or custom commands for a TinyPilot / ray.py interface.

Note: I had to add the following to /boot/config.txt (after enabling serial port and disabling serial console in raspi-config):

`dtoverlay=pi3-miniuart-bt`
