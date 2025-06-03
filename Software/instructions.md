run "sudo nano /boot/config.txt" and add the text that is saved in config.txt and save

than "sudo reboot"

after it restarts run "sudo raspi-config"

go to "Advanced Options" than "Audio" and "Force 3.5mm (headphone) jack"

than run "alsamixer" and turn the audio up

to test it out run "aplay /usr/share/sounds/alsa/Front_Center.wav"
