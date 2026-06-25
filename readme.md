 # The Onekey
 ## The one key and knob macropad(available at onekey.hackclub.com)
 ## Features
 - Sandwhich mount for constistency of feel
 - Magnetic Pogo Pin connectors for easily bonding the two sides of the macropad. 
 - Xiao RP2040 for cost efficiency
 - Neopixel for shiny
## Reasons I built this
 - @maxstellar on slack asked me to help with his internship project, so I did!
## Schematic
These schematics are very concise, it's just a MCU, whatever input device, and magnetic pogo pin connectors(generic symbol). Plus neopixel for key. First one is encoder, second is keyswitch
 - ![Encodersch](<assets/Screenshot 2026-06-25 at 6.14.21 PM.png>)
 - ![Switchsch](<assets/Screenshot 2026-06-25 at 6.14.46 PM.png>)
## PCB
 I designed the encoder PCB especially with a lot of care because the pcb had to stick out enough to reach into the case of the main onekey. The pcb with the key also took some time because at first I decided hotswap, but then changed to normal switches. I then made these basically centered. Also I had to work a bit on routing for the neopixel
  ### Keyswitch PCB
  ![Left](<assets/Screenshot 2026-06-25 at 6.09.13 PM.png>)
  ### Encoder PCB
  ![Full](<assets/Screenshot 2026-06-25 at 6.14.12 PM.png>)
## CAD
 I designed the CAD with portability, usability, and elegance in mind. I also had to design it with both a cutout for the USB and pogo pin connector. 
 ### Bottom Case of Encoder
 ![Bottom](<assets/Screenshot 2026-06-25 at 6.12.07 PM.png>)
 ### Top Plate of Encoder
 ![Plate](<assets/Screenshot 2026-06-25 at 6.12.24 PM.png>)
 ### Bottom Case of Keyswitch
 ![Bottom](<assets/Screenshot 2026-06-25 at 6.11.59 PM.png>)
 ### Top Plate of Keyswitch
 ![Plate](<assets/Screenshot 2026-06-25 at 6.12.54 PM.png>)
 ### Encoder Assembly
 ![EncoderAssembly](assets/8dfb5017-fdaa-4beb-a9fc-a19013720f98.PNG)
 ### Keyswitch Assembly
 ![KeyAssembly](assets/onekeyassemble_2026-Jun-25_10-17-34AM-000_CustomizedView7173037740.png)
 ### Full Assembly
 ![Assembly](assets/48f44c55-8ea5-4062-9919-0f438c232144.PNG)
## Firmware
### The whole point of this YSWS is for people to create their own firmware for a one key macropad, so I don't have firmware here. 
## My Zine
![zine](assets/zine.png)
Zine is at zine.pdf too
## Assembly Instructions
 - First, obviously fabricate the PCB and solder everything.
 - Next is printing the plates and cases.
 - This is pretty simple, it was designed with tolerances, you can keep it at basically whatever setting
 - Put heatset inserts through the bottom of the cases
 - Then just screw the pcb and the bottom case together via those
 - Then put the plate on
 - Put the keycap on the switch
 - You have a Onekey!
## BOM
| Description                | Price             | Link                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :------------------------- | :---------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cherry MX Switch           | 0.89              | https://www.aliexpress.com/item/1005012226589276.html?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Rotary Encoder             | 0.77              | https://www.google.com/aclk?sa=L&ai=DChsSEwiDmf3MwqGVAxVMsgMAHSXIKaQYACICCAEQBhoCb2E&co=1&gclid=CjwKCAjwgO7RBhBKEiwAZNP85rsEmMWYl6g3VWZC5sRsF7ipgr_IHMzRDROKCq-PEOmagNYKbJWF8xoCA8UQAvD_BwE&cid=CAASugHkaLFY9NzucKKfRV9B6g7XEAqV9XkwZMdLsUDu2WDWrsWXZWfksITytF0U-4hzBTNQWbPV-MTb6yh8duZl9zGyLDUE2ipN-ISwgdL_gcXBXNhNxFtpJ2sveYj4UtoBmcYsorckyzbGdYKRD1rP_M9QV_JRDvF--RkA4PA8LLqQ30VgbJ3ZiJvVUGqgRd4tz5SxRPMyOoW_mR5yP6VgMLnE_8iheHBv7Mp09K1dmTv7WgK8nhcIEHBx4jw&cce=1&sig=AOD64_0N9GGjKSBzXkcAyZ8kAby49MiS1g&ctype=5&q=&ved=2ahUKEwiK2PXMwqGVAxUJkGoFHUd8NIgQ5bgDKAB6BAgJEBM&adurl= |
| Xiao RP2040                | 0.7               | https://www.aliexpress.us/item/3256804273304037.html?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Pair of Magnetic Pogo Conn | 6.5               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| PCBs from JLCPCB           | Will Cover Myself |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Total                      | 9.31              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

## Credits
 This project was helped by @owais. Thanks to fallout for sponsoring this!
