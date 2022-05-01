# sounddrivers

Logbook of my journey towards fixing the Dummy Output audio for my *matebook d15*.

Everything tested since now is listed in `attempts`.
## Format

the `stats` folder contains the output of 

lshw 				[lists hardware (use -short to get less info)]
lspci
cat /proc/asound/devices 	[lists all the devices as seen by ALSA (hw:0,0) ]
ls -l /dev/snd 			[lists all sound devices by name]
aplay -l 			      [listst alsa available cards]
pacmd list-cards 		[pulseaudio available cards]

for a given setting.
