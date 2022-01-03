# Whale-Engine
CMOS based optical drone synthesiser

Youtube video: https://youtu.be/fdHDt4L-P9A

Everything you need to build one of these is included. This is not a 'true' beginner project, some mechanical and electrical skills are required.
Some assumptions will need to be made with drilling and wiring the output jack and power input jack.
The PCB files are formatted for JLC manufacture. The original PCB was hand etched so the schematic includes jumpers. These can be ignored if you
order a PCB.

The finished device draws 50mA at most, making it suitable for battery or USB power. Do not connect more than 9V, the zener diode regulation is very crude.
The output is not suitable for powering headphones and benefits from being connected to an amplifier. It is designed to be connected to an amplified speaker.

Known issues:
- Even with modulation switches set to off, the modulations oscillators have an effect on the primary oscillator.
  This could be fixed by using a separate 4093 IC for the modulation oscillators. In one unit, I isolated the LEDs with
  a transistor and the issue was still there. 
  The problem is only with a TI CD4093, the now obsolete OnSemi CD4093s I have do not exhibit this.
  This isn't a refined product, it was built for kids christmas presents.
  
MAG-03/01/2022
