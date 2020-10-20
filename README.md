# Skin Orchestra
Simple circuit to turn an Android phone into a MIDI/OSC skin touch sensor.

![Board](board.png)
![Schematic](schematic.png)


## Concept

This circuit is an oscillator which runs on the phantom power that can be extracted from a cheap Android smartphone's microphone jack. Therefore, a low current CMOS 555 timer must be used. Check your phone's specifications before connecting this circuit - you use it completely at your own risk.

Once plugged into an Android phone, the pads marked "skin" can be bridged by skin contact, which produces a variable frequency square wave across the microphone input.

You can use this "as is" for a simple tone, but this signal can also be processed by an Android app, which counts the zero-crossing frequency of the square wave and converts it to MIDI or OSC (app coming soon).


## Usage

You can give one wire to somebody else, and hold the other yourself. The harder you squeeze them, the higher the notes will be from the circuit.


## Safety

Use this design at your own risk. Do not plug the phone into a charger and then connect it to someone - there should never be a conductive connection between a person's body and a device wired to mains power.


## Acknowledgements

This project is a concept developed by Alma Edelstein-Feinsilber, James Hudson, and Patricio Zarazaga, to allow skin-touch control of musical instruments in 2014.