# Fuzz-Pedal
What is a fuzz pedal? What is a guitar pedal?

A guitar pedal is a device that can alter the sound of electronic instruments, namely electric guitars. There are several types of guitar pedals such as overdrive, distortion, fuzz, delay, phaser, buffer, the list goes on. If you play games, think of it like a mod for your game that can enahnce or alter your gameplay experience, in the same way guitar pedals can bring unique sounds to the musician.

The fuzz guitar pedal produces a sound akin to a faulty amplifier (I believe faulty components also led to this pedal being "discovered"). Have you ever heard someone talk into a mic and someone tells them their mic is clipping? Well with a fuzz pedal, that is what we are trying to achieve to a certain extent. 


![image](https://github.com/ammar3443/Fuzz-Pedal/assets/124750847/7b19b68a-85c5-4b4b-997f-30a442044553)

The image above is the circuit we will implement. The input audio jack is connected to the 2.2uF capacitor. The output jack is connected to potentiometer X2.
In this project I am using PNP transistors, but NPN transistors can be substituted with modifications to the circuit of course.
Component list:

1       0.01 uF,
1       2.2uF,
1       20uF,
1       470Ω,
1       8.8KΩ,
1       33KΩ,
1       100KΩ,
1       1KΩ (Linear pot),
1       500KΩ (Audio taper pot),
2       2N3906 transistors,

Jack in, Jack out, battery clip, battery

![image](https://github.com/ammar3443/Fuzz-Pedal/assets/124750847/3722ab0d-52dd-4f56-afb0-b30fe12aec96)

Heres an image of the basic circuit minus the audio jack and potentiometer.

Currently working on a PCB design for this circuit.
