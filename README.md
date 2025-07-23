# RP0-HandHeld
Raspberry Pi Zero 2 gaming handheld, that runs Retro Pie...

I always wanted gaming console that has retro games in it so I made this!

![RP0-HandHeld 1](https://github.com/user-attachments/assets/9f5c7344-b431-43ad-ba77-fc917238c52f)

![RP0-HandHeld 2](https://github.com/user-attachments/assets/c5a896a8-a875-4fac-bd7d-4578ff403f85)

It consists of few key parts:
- [Screen](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/edit/main/README.md#screen)
- [Audio](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/edit/main/README.md#audio)
- [Battery and charging](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/edit/main/README.md#battery-and-charging)
- [Inputs](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/edit/main/README.md#inputs)
- [PCB](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/edit/main/README.md#pcb)
- [Case]()
- [Software]()

You can read about how I designed it in [JOURNAL.md](https://github.com/OndrejVacekSPSCL/RP0-HandHeld/blob/main/JOURNAL.md).

## Screen
I found this [screen](https://tinyurl.com/3287bkxc) online. It has the perfect size for my project.

![image](https://github.com/user-attachments/assets/4f11b6bc-cf0a-4dfb-bcf8-76fd139d4978)

## Audio
Audio is made with help of this [tutorial](https://youtu.be/3pXB90IDNoY?si=AYgq76n8aVKT-kv3).

Parts list:
- 2x [270 Ohm resistors](https://tinyurl.com/ycs5rh84)
- 2x [150 Ohm resistors](https://tinyurl.com/ycs5rh84)
- 2x [10 uf electrolitic Capacitors](https://tinyurl.com/2p6z8e5f)
- 2x [0.01 uf Polyester-Film Capacitors](https://tinyurl.com/33zae35e)
- [Speaker](https://tinyurl.com/4ueak527)
- custom PCB

This is how they should be conected:

<img src="https://github.com/user-attachments/assets/59e63e07-29d2-48de-9986-08d0493ad39c" alt="image" width="400"/>

## Battery and charging
This device is powered by [2000mAh battery](https://tinyurl.com/25jmx5w2) It uses [voltage booster](https://tinyurl.com/4jvbk29v) (3.7V on battery -> 5V for screen and RP0), [battery charge indicator](https://tinyurl.com/5596b6uh), switch and [USB-C port](https://tinyurl.com/2bktbsuc) for charging.

<img src="https://github.com/user-attachments/assets/556fb7b3-e956-4b3f-b37c-78652f554b3c" alt="image" width="600"/>

## Inputs
This game console will use [rubber dome switches](https://www.aliexpress.com/item/32866761020.html). Those are used in normal gamepads. They will be attached like this:

<img src="https://github.com/user-attachments/assets/664cb555-08ad-40a6-a7b1-2bbbb6a56652" alt="image" width="600"/>

## PCB
This is the PCB:

<img src="https://github.com/user-attachments/assets/6e7682e6-b841-4d3d-9538-a29a6f9921ee" alt="image" width="600"/>

![RP0-HandHeld](https://github.com/user-attachments/assets/1bd03e6e-5736-45a1-b495-a285cecf7395)

## Wiring diagram
This shows, how to wire everything together:

![Bez názvu](https://github.com/user-attachments/assets/2d17e2b5-b506-4dee-afbb-e24fdcff0acd)

## Case
Case is made from few 3D printed pieces.

## Software
It runs RetroPie. It is needed to tweak with few files to get the buttons running.

## BOM
|Part                                   |Quantity needed|Quantity in set|Price(USD)|Shipping(USD)|Note                                                       |Link                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------|---------------|---------------|----------|-------------|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Raspberry Pi zero 2W                   |1              |1              |30.65     |Free         |Might buy locally. That would be ~23.5 USD with shipping...|https://www.aliexpress.com/item/1005005876463565.html?spm=a2g0o.productlist.main.28.dd93M2cRM2cRkk&algo_pvid=0be3d98c-6e9c-4fd2-ac85-0cc95946d9b3&pdp_ext_f=%7B%22order%22%3A%2217%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                  |
|Touch screen                           |1              |1              |31.41     |8.95         |                                                           |https://www.aliexpress.com/item/1005007372530555.html?spm=a2g0o.productlist.main.15.1b4f6ebfXAxVwS&algo_pvid=778947cf-06f8-42e1-ab42-ae633efbac38&pdp_ext_f=%7B%22order%22%3A%2229%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                  |
|470 Ohm resistors                      |2              |20             |0.87      |1.20         |                                                           |https://www.aliexpress.com/item/1005006546596146.html?spm=a2g0o.productlist.main.12.51d0e0eWe0eW7e&aem_p4p_detail=202505280633577728206491438800001674218&algo_pvid=563641ed-a55b-4103-a241-aa406c07ccdc&pdp_ext_f=%7B%22order%22%3A%22220%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202505280633577728206491438800001674218_3                  |
|270 Ohm resistors                      |2              |20             |0.87      |1.20         |                                                           |https://www.aliexpress.com/item/1005006546596146.html?spm=a2g0o.productlist.main.12.51d0e0eWe0eW7e&aem_p4p_detail=202505280633577728206491438800001674218&algo_pvid=563641ed-a55b-4103-a241-aa406c07ccdc&pdp_ext_f=%7B%22order%22%3A%22220%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202505280633577728206491438800001674218_3                  |
|150 Ohm resistors                      |2              |20             |0.87      |1.20         |                                                           |http://aliexpress.com/item/1005006546596146.html?spm=a2g0o.productlist.main.12.51d0e0eWe0eW7e&aem_p4p_detail=202505280633577728206491438800001674218&algo_pvid=563641ed-a55b-4103-a241-aa406c07ccdc&pdp_ext_f=%7B%22order%22%3A%22220%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202505280633577728206491438800001674218_3                       |
|10 uf electrolitic Capacitors          |2              |30             |1.23      |Free         |                                                           |https://www.aliexpress.com/item/32895970824.html?spm=a2g0o.productlist.main.5.7f181376hRWTwp&algo_pvid=f10a86c9-43e2-4b39-b7d6-3c051a2da662&pdp_ext_f=%7B%22order%22%3A%22698%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                       |
|0.01 uf Polyester-Film Capacitors(103J)|2              |20             |2.50      |Free         |                                                           |https://www.aliexpress.com/item/1005007139328345.html?spm=a2g0o.productlist.main.2.cdd17d2bVzZAMp&algo_pvid=cc98d625-be03-45d7-bbcc-97f77622ac93&pdp_ext_f=%7B%22order%22%3A%22633%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                  |
|Speaker                                |1              |2              |3.95      |Free         |                                                           |https://tinyurl.com/22fu8ykr                                                                                                                                                                                                                                                                                                                                                                |
|Audio amplifier                        |1              |1              |1.29      |Free         |Alternative to Adafruit Mono 2.5W Class D Audio Amplifier  |https://www.aliexpress.com/item/1005005926858790.html?spm=a2g0o.productlist.main.1.11c565f9vHiI2T&algo_pvid=420fbc1b-d5dd-49c2-b003-ea5fa3fb3f9b&pdp_ext_f=%7B%22order%22%3A%22199%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                  |
|PCB                                    |1              |5              |NaN       |NaN          |                                                           |                                                                                                                                                                                                                                                                                                                                                                                            |
|Switches                               |10             |10             |1.03      |1.08         |                                                           |https://www.aliexpress.com/item/32866761020.html                                                                                                                                                                                                                                                                                                                                            |
|Wires(28AWG)                           |1              |1              |3.00      |Free         |                                                           |https://www.aliexpress.com/item/1005007009685328.html?spm=a2g0o.productlist.main.8.634668fbpAXrhc&algo_pvid=342edcb8-3134-494d-9a3c-5d4d930c2bdb&pdp_ext_f=%7B%22order%22%3A%223728%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                 |
|Battery                                |1              |1              |13.82     |Free         |                                                           |https://www.aliexpress.com/item/1005008087303778.html?spm=a2g0o.productlist.main.9.575382a8DGjkdq&algo_pvid=d637d23c-15aa-495d-ab4d-8912fa393757&pdp_ext_f=%7B%22order%22%3A%2271%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                   |
|PWR Switch                             |1              |5              |1.63      |Free         |                                                           |https://www.aliexpress.com/item/32873386670.html?spm=a2g0o.productlist.main.5.2316331bN0M5D9&algo_pvid=b8820c4a-1f17-47ad-b5a4-cc75b5f47f7d&pdp_ext_f=%7B%22order%22%3A%223707%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                      |
|Voltage booster(5V)                    |1              |1              |0.94      |0.48         |                                                           |https://www.aliexpress.com/item/1005006342017830.html?spm=a2g0o.productlist.main.8.32124802Irvy0q&aem_p4p_detail=2025052709294011340235084993920000692888&algo_pvid=8fda0b9d-ede4-480d-a92e-be31044526a9&pdp_ext_f=%7B%22order%22%3A%2299%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=2025052709294011340235084993920000692888_2#nav-specification|
|USB-C inupt with cables                |1              |5              |2.33      |Free         |                                                           |https://www.aliexpress.com/item/1005007469640237.html?spm=a2g0o.productlist.main.1.2786577a5POLVK&algo_pvid=42de749d-264f-41c6-88d9-8b5cbc3e668d&pdp_ext_f=%7B%22order%22%3A%223195%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                 |
|Battery charge indicator(1S)           |1              |1              |0.94      |0.65         |                                                           |https://www.aliexpress.com/item/1005006713968836.html?spm=a2g0o.productlist.main.13.1c546373Ro11DZ&algo_pvid=052297d2-3386-4d60-a0eb-261dbd806c3b&pdp_ext_f=%7B%22order%22%3A%22414%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A                                                                                                                                 |
|Total                                  |               |               |112.10    |             |Price with shipping                                        |                                                                                                                                                                                                                                                                                                                                                                                            |
