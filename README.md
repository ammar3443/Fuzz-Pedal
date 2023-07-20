# Fuzz-Pedal

The fuzz guitar pedal produces a distorted sound, hence the name fuzz pedal. To achieve this effect, two common emitter transistors are connected in cascade. Both transistors have their emitter regions grounded. 

In this project I am using PNP transistors, but NPN transistors can be substituted with modifications to the circuit of course.
![image](https://github.com/ammar3443/Fuzz-Pedal/assets/124750847/7b19b68a-85c5-4b4b-997f-30a442044553)

The image above is the circuit we will implement. The input audio jack is connected to the 2.2uF capacitor. The output jack is connected to potentiometer X2.

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

Jack in, Jack out, battery clip, battery, & DPDT foot-switch
