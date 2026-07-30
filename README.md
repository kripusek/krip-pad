# krip-pad
This is my macro pad madwe mainly for playing osumania type games

## Features
- A 0.91 inch OLED display
- 4 keys
- An opening to see the screen, xiao rp2040 and the oled

## PCB
Here are pictures of my pcb:

| **Schematic** | **PCB** |
|---------------|---------|
|![](https://i.postimg.cc/2SqSDYJB/Bez-tytulu.png)|![](https://i.postimg.cc/L5C2cQ3Z/sm-purple-top.png)|
 

## CAD
I designed it using autodesk fusion


Everything fits together with 5 m3 screws and bolts

## Firmware

I wrote the firmware using qmk.

## Notes
If you want to change the mapped you can use via with the included via.json file which you can find in the firmware folder https://usevia.app/

Making this pad was fun, I got to learn qmk fusion and kicad which I can use fluently now, fusion and qmk not so much.

I have used https://github.com/hackclub/hackpad/blob/main/hackpads/cyaopad/README.md as a template for my readme

I have used https://github.com/dancarroll/qmk-bongo for the bongo animations
I have also used ai for explaining what does what in qmk, afterwards I have written the code myself and ai has helped me debug it.

## BOM
- 1 SEEEDUINO XIAO RP2040
- 4x any switch mx style
- 4x 1N4148 diodes
- 1x default 32x128 with GND-VCC-SCL-SDA pin order
- 5x same screws as orpheuspad and corresponding nuts
