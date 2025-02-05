![image](https://github.com/user-attachments/assets/c70492e7-fd8f-4250-90b6-e0bec71d82e6)

# FightBoard-Tester
A Simple Design to Test common form factor fighting boards. This connects directly across the common 20 pin header as well as the JST PH-5 and PH-4 connectors for common connectors. Each possible button input is on a dipswitch connecting GROUND to the signal in order to test behaviors on boot in any combination required. Ideally, the LEDs for the corresponding input, light up as well when the dipswitch is in the "ON" position indicating a button is held down.

From left to right, as indicated on the board, there are three dipswitch banks:

First: U, D, L, R
Second: P1, P2, P3, P4
Third:  K1, K2, K3, K4
Fourth: START, SELECT, HOME, TP CLICK
Fifth: L3, R3. The final two positions are unconnected.

The momentary switch is a turbo button. Id didn't make sense to include it as a dipswitch as that's not a potential use case in real life.

Player LEDs and Turbo LED functions such that they always have 3V applied, but are turned on when the corresponding pin on the fight board is sent low. This is a common way to drive these LEDs and Brook has done it for years. The PS360+ that preceeded most of the newer boards did it this way as well. Always confirm these details before connecting things.

The JST connectors are "reversed" from those on the fighting board so you would connect Pin 1 to Pin 5, Pin 2 to Pin 4, Pin 3 to Pin 3, Pin 4 to Pin 2, and Pin 5 to Pin 1. This look slike wires are directly connected between the PCBs in a straight line. 

As of 2.4.25 - this is an untested design.


#License
This design is licensed under CC-NC-BY-SA-4.0. Details can be found here: https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en

You are free to:
Share — copy and redistribute the material in any medium or format
Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:
*Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
*NonCommercial — You may not use the material for commercial purposes .
*ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
