## Installing RetroPie
Install [RaspberryPI](https://www.raspberrypi.com/software/) imager to your host OS.

Than chose device (Raspberri Pi zero 2 W). Than chose OS -> Emulation and games OS -> RetroPie -> RetroPie 4.8 (RPI 2/3/Zero 2 W).

Insert your micrioSD card (chose minimum 32GB card) and select it.

It should look something like this:

![image](https://github.com/user-attachments/assets/30bc6b0b-a987-4e76-be16-a6e3e656dc9f)

When it finishes unplug it, put it in your RaspberryPI and power it on

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

When you finish configuration chose EXIT.
Than run:
- gpionext set pins 3,5,7,15,26,29,31,35,38,40
- gpionext start
- sudo reboot now

When it reboots it shoud show that nothing has been configured yet, but it should detect our controller. Hold one of the buttons ant it shoud start the configuration process. To skip oveer the buttons that we don't have just press and hold one button (for example select).

## Audio
run "sudo nano /boot/config.txt" and add the text that is saved in config.txt and save

than "sudo reboot"

after it restarts run "sudo raspi-config"

go to "Advanced Options" than "Audio" and "Force 3.5mm (headphone) jack"

than run "alsamixer" and turn the audio up

to test it out run "aplay /usr/share/sounds/alsa/Front_Center.wav"

## Installing games
To install your favourite games to our console you'll need usb stick (it is recomended to use one with activity light). Plug it into your computer and create folder named retropie

![image](https://github.com/user-attachments/assets/475a97fd-5520-4d1d-b9ec-ad954441e789)

Than connect it to your RPI and wait for a few minutes (or whan the activity light stops blinking). Than put it back into your PC. When you open the retropi folder you shoul see something like this: 

![image](https://github.com/user-attachments/assets/2b1e2836-15e2-476c-b1b9-517661f28aa6)

When you open the roms folder you should find this: 

![image](https://github.com/user-attachments/assets/351c13e1-bab3-4116-aaa0-b97c9e8e8819)

Than just put your games into the coresponding folders...

Than connect it to your RPI and it wil transfer the games files. Wait untill the activity light stops blinking.

Than go into the RetroPie MAIN MENU  -> QUIT -> RESTART EMULATIONSTATION

After that you should see your games in the RetroPie menu :)
