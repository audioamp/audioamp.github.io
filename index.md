# Welcome to Audio Amp

Audio Amp is an Open Source Hardware (OSHW) kit for teaching audio electronics in a lab setting.
It is designed to engage students at two levels of electronics experience:

1. *Beginner students* will learn how the system works at the block diagram level and experiment with how different audio tones sound and look on the oscilloscope.
2. *Intermediate/advanced students* will learn how the opamp and transistor circuits work at the component level and learn how to solder on a PCB.

The design files for this kit can be found in [our Github repository](https://github.com/audioamp/audioamp) and are licensed under the [TAPR Open Hardware License](https://www.tapr.org/ohl.html).


# Table of Contents
1. [Curriculum Goals](#curriculum-goals)
	1. [Beginner level](#beginner-level)
	2. [Intermediate level](#intermediate-level)
	3. [Advanced level](#advanced-level)
2. [Circuit Design](#circuit-design)
	1. [Schematic and Simulation](#schematic-and-simulation)
	2. [Breadboard version](#breadboard-version)
	3. [PCB version](#pcb-version)
3. [Cost](#cost)
4. [Additional Equipment](#additional-equipment)
5. [Future Work](#future-work)
6. [About Us](#about-us)


## Curriculum Goals <a name="curiculum-goals"></a>
### Beginner level <a name="beginner-level"></a>
* See and hear the difference between *sine and square waves*
* See and hear the effect of *clipping distortion*
* See and hear the effect of *low pass and high pass filters*
* See and hear the effect of *guitar pedals*

### Intermediate level <a name="intermediate-level"></a>
* Construct and calculate gain of a *non-inverting opamp amplifier*
* Understand how an opamp with *negative feedback* can *correct for amplifier non-linearity*
* Understand how to bias a *single-supply opamp*

### Advanced level <a name="advanced-level"></a>
* Understand how a *VBE multiplier* (aka. "rubber diode") works
* Construct and bias a *Class AB amplifier*


## Circuit Design <a name="circuit-design"></a>
### Schematic and Simulation <a name="schematic-and-simulation"></a>
<img src="assets/audioamp_LTSpice_schematic.png" width="50%">

<img src="assets/audioamp_LTSpice_waveforms.png" width="50%">


## Breadboard version <a name="breadboard-version"></a>
<img src="assets/audioamp_breadboard.jpg" width="50%">


## PCB version <a name="pcb-version"></a>
<img src="assets/audioamp_PCB_v1.1.png" width="50%">


## Cost <a name="cost"></a>
Prices are assuming low quantities (under 10 units). Significant savings can be had by purchasing in bulk.  
Prices are for purchasing within the US in October 2019.  
Cost of additional equipment is not included.  

Cost breakdown:

* $5 per PCB from PCBWay
* $x Digikey components
* $x Newark components
* $x 12V power supply
* $x box enclosure from Adafruit

Total cost per unit: **$x**

Currently, we are not selling pre-made kits. However, if there is significant interest, we may start a crowdfund to manufacture and distribute these kits.

## Additional Equipment <a name="additional-equipment"></a>
To make use of Audio Amp, you will need additional equipment:

* 8Ω speaker with banana plug jacks
* oscilloscope
* waveform generator
* banana cables
* BNC cables

Of course, you don't need to have a top-of-the-line oscilloscope and waveform generator to make use of Audio Amp.
Even a simple USB oscilloscope like the $30 [EspoTek Labrador](https://espotek.com/labrador/) would work!
And any smartphone with an audio jack can work as a make-shift function generator.

For additional bells-and-whistles, consider getting these:

* *Bluetooth-to-aux receiver* to use phones without an audio jack
* *Spectrum analyzer* or oscilloscope with *FFT* capabilities to analyze audio signals in the frequency domain


## Future Work <a name="future-work"></a>
* Make a *stereo amplifier* so students can experiment with phase differences between 2 channels, and utilize the XY mode on an oscilloscope.
* Make an *interactive graphical simulator* so students without access to any lab equipment can perform all the experiments.


## About Us <a name="about-us"></a>
This kit was created by [William Meng](https://williammeng.com/) with the guidance and support of David Vallancourt.

© William Meng 2019. The contents of this webpage are licensed according to CC BY-SA 4.0.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
