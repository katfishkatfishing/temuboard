# temuboard

<img width="1409" height="684" alt="image" src="https://github.com/user-attachments/assets/fbd0b2ba-f911-475b-8d11-a31ca354ec6a" />

A compact 75% mechanical keyboard taken inspiration from the Keycool 84, that has a rotary encoder, and a small OLED display.

---

## Features

- **79 keys** (78 keys + rotary encoder button)
- **EC11 Rotary Encoder** - rotation bound to volume, button bound to mute.
- **128x64 I2C Display** - to play tiny animations.
- **Custom MCU** - for extra I/O pins.
- **RMK firmware** (?)
- **Bottom mount style** - Bottom case, plate, Cherry MX switches, top case.

---

## Case Bottom

Case screws: M3
<img width="1281" height="631" alt="image" src="https://github.com/user-attachments/assets/60296ab8-d52d-41c3-bcce-68f556a049be" />
<img width="846" height="380" alt="image" src="https://github.com/user-attachments/assets/477ef920-be6d-49ef-8285-9b4ba70e5f27" />
<img width="1160" height="615" alt="image" src="https://github.com/user-attachments/assets/f87dadb5-aa8e-40cb-a543-5c4c97a0fcfd" />
<img width="1155" height="321" alt="image" src="https://github.com/user-attachments/assets/77131ea6-ff6d-403c-ae45-54f402824f43" />

---

## Case Top

<img width="1151" height="582" alt="image" src="https://github.com/user-attachments/assets/81d20d26-2258-479b-9fac-6c625ce15b7c" />
<img width="1159" height="242" alt="image" src="https://github.com/user-attachments/assets/1263ee79-d03a-4763-bcda-ead037b39018" />

---

## Plate

<img width="1078" height="510" alt="image" src="https://github.com/user-attachments/assets/673b1588-5775-4bd2-b311-759cdca4a7b6" />
1.5mm thickness

## Pin Mapping

| Function | Pin |
| --- | ---|
| Columns (col 1-15) | PA 0-2,6,7, PB 12-15, PC 4-9 |
| Row (row 1-6) | PA3, PB 0-2, 10,11 |
| Encoder A/B | PA8/PA10 |
| OLED SDA/SCL | PB6/PB7 |
| Crystal In/Out | PH0/PH1 |
| D+/D- | PA11/PA12 |

<img width="1660" height="894" alt="image" src="https://github.com/user-attachments/assets/e5a66a0c-9616-44ab-ae0f-451068dd2e3c" />
<img width="1663" height="689" alt="image" src="https://github.com/user-attachments/assets/e1348dc0-959a-4287-a88a-baaa524fdbb7" />
<img width="1535" height="707" alt="image" src="https://github.com/user-attachments/assets/016bb7b7-f00e-496d-b696-be8da677b752" />
<img width="975" height="428" alt="image" src="https://github.com/user-attachments/assets/2da4dde5-e6ae-4e82-a0a8-1d746bb9ddd6" />
<img width="1178" height="497" alt="image" src="https://github.com/user-attachments/assets/aed3ae68-4b25-41cd-81e7-43f9d0e9a34b" />

---
## Firmware

---
## PCB/Assembly Note

---
## Lessons learnt
- As a complete beginner to these things, I learnt so much about, planning out schematics, routing PCBs, and CAD. When I first started this project I didn't even know I had to make the keyboard layout. So, I had a friend of mine (thephantompx) that has more experience to guide me through the first few days of using Kicad and setting up the schematics. He gave me advice on the components needed, how to connect them, and also taught me how to route the PCB. We ran out of I/O pins on the Pico pi so we found a suitable MCU and made our own board. CAD was horrid. I used FreeCAD because OnShape was laggy for me. It took me 2 days to figure out how to even make a sketch, and the tutorial I was following didn't really teach too much of what I needed, just enough to get me started. Tbh I didn't think it'd take this long, but then again I started with literally 0 experience. This project was a great opportunity for me to use my free time to get experience on how to design things.



