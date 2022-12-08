# 9Pin_BreakoutEx
Breakout board for 9 pin mini DIN connectors with additional features for audio and sync.

![9P Breakout Isometric View](/Images/Overview.jpg)

Leaving the jumpers un-bridged and components empty means the board will act like a standard 9 pin breakout DIN.

If attaching to a system that doesn't have composite and only has a 5V TTL level sync, use the following BOM:

C1: 220uF 6.3V Tantalum 3528 size capacitor
R1: 620 Ohm 1/8W 0603 size Resistor
R2: 86.6 Ohm 1/8 0603 size Resistor

RGB mods for older consoles tend to make the user decide between Composite Video level sync or TTL sync. With this breakout, simply install the resistors and capacitor (value indicated on bottom silkscreen) and use the TTL sync from the RGB modification. This will simultaneously deliver a proper sync voltage to the Composite Video pin on the DIN for using HD Retrovision cables. ***ENSURE THE RGB MOD CAN DRIVE TWO 75 OHM LOADS (Such as THS7374, THS7314 or similar) ***

The solder jumper for audio can be used as follows:
-Right: Connects Right and Left audio nodes, passes to both pins.
-Left: Connects Right audio to the Mono pin

Both jumpers can be soldered to make sure a mono audio signal goes to all of the audio pins.
