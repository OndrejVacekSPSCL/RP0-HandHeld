---
title: "RP0 Handheld"
author: "Ondkos"
description: "Raspberry Pi Zero 2 gaming handheld console that runs on RetroPie!"
created_at: "2025-05-26"
---

## 27th May: Start of the project
Yesterday i started thinking about this project. I was searching the web for suitable RP and settled on RP Zero 2W. It should have enought power to run some games on RetroPie. I chose the zero 2W, becouse it is really small. That is usefull because i am making handheld.

Today I started searching the web for other parts.

I will need:

- Screen
    
- Some way to get audio
    
- Inputs
    
- Battery and charging module.

 ### Screen
 First i started looking for display. I wanted somethig between 4" and 6". I was thinking about [this one](https://www.amazon.de/dp/B085TC5YMR?ref=myi_title_dp&th=1) or [this one](https://tinyurl.com/ev4p9sd7), but they were to small. Than I found this [5" display](https://tinyurl.com/3287bkxc) (the touch variant for easier manipulation). Downside on this one is that it uses HDMI and not the pins on the RP.

![image](https://github.com/user-attachments/assets/4f11b6bc-cf0a-4dfb-bcf8-76fd139d4978)


### Audio
 Than I started to think about the audio. There are three ways I can get it from RP0.
 
1. Buy cheap USB dongle
    
2. Buy [premade DAC HAT for RP](https://shop.pimoroni.com/products/audio-amp-shim-3w-mono-amp?variant=32341591064659)
    
3. Make my own audio output system with help of [tutorial](https://youtu.be/3pXB90IDNoY?si=AYgq76n8aVKT-kv3)
    
I was thinkig about the second option, but than I said to myself that It would be to easy :D. I will need:

- 2x [270 Ohm resistors](https://tinyurl.com/ycs5rh84)
- 2x [150 Ohm resistors](https://tinyurl.com/ycs5rh84)
- 2x [10 uf electrolitic Capacitors](https://tinyurl.com/2p6z8e5f)
- 2x [0.01 uf Polyester-Film Capacitors](https://tinyurl.com/33zae35e)
- [Speaker](https://tinyurl.com/4ueak527)
- custom PCB

Here is schematic of how it should be connected

<img src="https://github.com/user-attachments/assets/59e63e07-29d2-48de-9986-08d0493ad39c" alt="image" width="400"/>

### Inputs
I looked into how game controllers work. I found this [reddit post](https://www.reddit.com/r/AskElectronics/comments/8lt9gv/what_kind_of_pushbuttons_do_game_controllers_use/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) and through the comments I found [those switches](https://www.aliexpress.com/item/32866761020.html). They are rubber dome switches, you could find something similar in membrane keyboards. Thay will be conected by [wire](https://tinyurl.com/4vmrkypu). I wanted to make PCB for them, but that would be harder to attach it to the case...

![image](https://github.com/user-attachments/assets/2c8c2739-ab02-4b8b-bf0d-f5d6dc86ce34)

### Battery and charging module
With the help of this [video](https://youtu.be/wPQf_Pz0APA?si=iIAJfkxdQpS1blh7) I learned how to charge the RP0 from battery. ~~I found [cheap voltage booster](https://tinyurl.com/429w3p3t), because the one he uses in the video is almost 15x more expensive.~~ I also found this [battery](https://tinyurl.com/25jmx5w2). Because I don't want to have the RP0 take the power all the time I also found those [switches](https://tinyurl.com/34hr93tu).

**Time spent: 5hr**

## 28th May: PCB and batteries

### Battery and charging module 
I found out that the vlotage booster i found yesterday doesn't suport charging... So I found [new one](https://tinyurl.com/4jvbk29v) that does. I wil also need some [USB-C inupt with cables](https://tinyurl.com/2bktbsuc). Because i also want to know how charged the battery is i will need [battery charge indicator](https://tinyurl.com/5596b6uh).

This is how it will look like:

<img src="https://github.com/user-attachments/assets/556fb7b3-e956-4b3f-b37c-78652f554b3c" alt="image" width="600"/>

### PCB
I started working on the PCB for my project. I found this [footprint](https://www.snapeda.com/parts/RASPBERRY%20PI%20ZERO%202%20W/Raspberry%20Pi/view-part/) of RP0 that I'll use.

I started working on the schematic, and created this:


<img src="https://github.com/user-attachments/assets/7131816d-9086-4aaf-9e25-67b31e1ef72d" alt="image" width="600"/>

I had lots of problems with finding the right footprints for the resistors and capacitors...

After some time I finished the PCB

<img src="https://github.com/user-attachments/assets/6e7682e6-b841-4d3d-9538-a29a6f9921ee" alt="image" width="600"/>

### Audio
I found parts (resistors, capacitors, etc.) and added the links to the list above.

**Time spent: 5.5hr**

## 29th May: Remaking the PCB
Today I relised the pcb is to big, so i started remaking it... I reduced it a lot.

Height: 97mm -> 69mm

Width: 88mm -> 70mm

Here is the new version of the pcb:

<img src="https://github.com/user-attachments/assets/2ed13aef-1bf1-43a1-a037-ff171e0d801e" alt="image" width="600"/>

I also started working on the case

**Time spent: 3hr**
