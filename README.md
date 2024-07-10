## This is the REPO rasberry pi video looper ##

The image used to flash the raspberry pi has already pi video looper installed 
image is compatible with Raspberry pi 2,3,4 not 5

still not confirmed if its compatible with pi 3b ($25)

Image does not have wifi or ssh enabeled. if needed that can be enabeled with
	sudo raspi-config

Raspi config needs to be done to expand the filesystem to allow videos to copy over to SD card

video_looper.ini needs to be copied over to the /boot directory on the pi sd card to enable copymode and analog video

