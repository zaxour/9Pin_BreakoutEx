# 9Pin_BreakoutEx
Breakout board for 9 pin mini DIN connectors with additional features for audio and sync.

Leaving the jumpers un-bridged and components empty means the board will act like a standard 9 pin breakout DIN.

RGB mods for older consoles tend to make the user decide between Composite Video level sync or TTL sync. With this breakout, simply install the resistors and capacitor (value indicated on bottom silkscreen) and use the TTL sync from the RGB modification. This will simultaneously deliver a proper sync voltage to the Composite Video pin on the DIN for using HD Retrovision cables. ***ENSURE THE RGB MOD CAN DRIVE TWO 75 OHM LOADS***

The solder jumper for audio can be used as follows:
-Right: Connects Right and Left audio nodes, passes to both pins.
-Left: Connects Right audio to the Mono pin

Both jumpers can be soldered to make sure a mono audio signal goes to all of the audio pins.
