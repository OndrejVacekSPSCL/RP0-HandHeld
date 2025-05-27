---
title: "RP0 Handheld"
author: "Ondkos"
description: "Raspberry Pi Zero 2 gaming handheld console that runs on RetroPie!"
created_at: "2025-05-26"
---

## 27. May: Start of the project
Yesterday i started thinking about this project. I was searching the web for suitable RP and settled on RP Zero 2W. It should have enought power to run some games on RetroPie. I chose the zero 2W, becouse it is really small. That is usefull because i am making handheld.

Today I started searching the web for other parts.

I will need:

- Screen
    
- Some way to get audio
    
- Inputs
    
- Battery and charging module.

 ### Screen
 First i started looking for display. I wanted somethig between 4" and 6". I was thinking about [this one](https://www.amazon.de/dp/B085TC5YMR?ref=myi_title_dp&th=1) or [this one](https://tinyurl.com/ev4p9sd7), but they were to small. Than I found this [5" display](https://tinyurl.com/3287bkxc) (the touch variant for easier manipulation). Downside on this one is that it uses HDMI and not the pins on the RP.

![obrazek](https://github.com/user-attachments/assets/4f11b6bc-cf0a-4dfb-bcf8-76fd139d4978)


### Audio
 Than I started to think about the audio. There are three ways I can get it from RP0.
 
1. Buy cheap USB dongle
    
2. Buy [premade DAC HAT for RP](https://shop.pimoroni.com/products/audio-amp-shim-3w-mono-amp?variant=32341591064659)
    
3. Make my own audio output system with help of [tutorial](https://youtu.be/3pXB90IDNoY?si=AYgq76n8aVKT-kv3)
    
I was thinkig about the second option, but than I said to myself that It would be to easy :D. I will need:

- 2x 270 Ohm resistors
- 2x 150 Ohm resistors
- 2x 10 uf electrolitic Capacitors
- 2x 0.01 uf Polyester -Fil Capacitors
- audio jack
- custom PCB

### Inputs
I looked into how game controllers work. I found this [reddit post](https://www.reddit.com/r/AskElectronics/comments/8lt9gv/what_kind_of_pushbuttons_do_game_controllers_use/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) and through the comments I found [those switches](https://www.aliexpress.com/item/32866761020.html). I will be making custom pcb to fit them.

### Battery and charging module
With the help of this [video](https://youtu.be/wPQf_Pz0APA?si=iIAJfkxdQpS1blh7) I learned how to charge the RP0 from battery I found [cheap voltage booster](https://tinyurl.com/429w3p3t), because the one he uses in the video is almost 15x expensive. I also found this [battery](https://tinyurl.com/25jmx5w2). Because I dont want to have the RP0 take the power all the time I also found those [switches](https://tinyurl.com/34hr93tu).

**Time spent: 5hr**
