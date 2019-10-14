# Welcome to Audio Amp

Audio Amp is an Open Source Hardware (OSHW) kit for teaching audio electronics in a lab setting.
It is designed to engage students at two levels of electronics experience:
1. *Beginner/introductory students*, who will learn how the system works at the block diagram level, and will be able to experiment with how different audio tones sound and look on the oscilloscope.
2. *Intermediate/advanced students*, who will learn how the opamp and transistor circuits work at the component level.

To make use of the Audio Amp, you will need additional equipment:
* 8Ω speaker with banana plug jacks
* oscilloscope
* waveform generator
* banana cables
* BNC cables

Of course, you don't need to have a top-of-the-line oscilloscope and waveform generator to make use of Audio Amp.
Even a simple USB oscilloscope like the $30 [EspoTek Labrador](https://espotek.com/labrador/) would work!
And any smartphone with an audio jack can work as a make-shift function generator.

For additional bells-and-whistles, consider getting these:
* Bluetooth to aux receiver, to work with phones that lack an audio jack
* Spectrum analyzer or oscilloscope with FFT capabilities, to analyze audio signals in the frequency domain


## Circuit Design
![LTSpice schematic](assets/audioamp_LTSpice_schematic.png)

![LTSpice waveforms](assets/audioamp_LTSpice_waveforms.png)


## Breadboard version
![breadboard version](assets/audioamp_breadboard.jpg)


## PCB version
![PCB version](assets/audioamp_PCB_v1.1.png)


## Cost
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


## Curriculum Goals
### Beginner level
* See and hear the difference between sine and square waves
* See and hear the effect of clipping distortion
* See and hear the effect of low pass and high pass filters
* See and hear the effect of guitar pedals

### Intermediate level
* Construct and calculate gain of a non-inverting opamp amplifier
* Understand how an opamp with negative feedback can correct for amplifier non-linearity
* Understand how to bias a single-supply opamp

### Advanced level
* Understand how a VBE multiplier (aka. "rubber diode") works
* Construct and bias a Class AB amplifier


## Future Work
* Make a stereo amplifier so students can experiment with phase differences between 2 channels, and utilize the XY mode on an oscilloscope.
* Make an interactive graphical simulator so students without access to any lab equipment can perform all the experiments.


## About Us
This kit was created by William Meng with the guidance and support of David Vallancourt.
