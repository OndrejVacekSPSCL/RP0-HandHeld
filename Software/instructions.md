## Audio
run "sudo nano /boot/config.txt" and add the text that is saved in config.txt and save

than "sudo reboot"

after it restarts run "sudo raspi-config"

go to "Advanced Options" than "Audio" and "Force 3.5mm (headphone) jack"

than run "alsamixer" and turn the audio up

to test it out run "aplay /usr/share/sounds/alsa/Front_Center.wav"

## Input
First We need to install [GPIOnext](https://github.com/mholgatem/GPIOnext)
in terminal type:
- cd ~
- git clone https://github.com/mholgatem/GPIOnext.git
- bash GPIOnext/install.sh

If it asks you if you want to run configuration manager type n (that means no :D)

Than type:  
  sudo python3 /home/pi/GPIOnext/config_manager.py --pins 3,5,7,15,26,29,31,35,38,40

Than chose: Joypad 1
Our console has 1 dpad so chose that. 
We also have:
- start button
- select button
- A
- B
- X
- Y

It will as you to press the buttons. Do it. It will look something like this:

![image](https://github.com/user-attachments/assets/7e8b76e9-b20c-406d-858a-4b08228a4692)

