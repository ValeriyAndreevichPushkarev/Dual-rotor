# Dual-rotor
Dual Rotor

This repo contains correct description of dual rotor scheme and how to achieve extra effiency.

Actually, Dual rotor motors are more suitable for high-speed applications.
Because of hysteresis and eddy currents, when you have lower power for hysteresis and eddy currents, than in motors with one rotors.

Power for eddy currents is P~f^2

Lets define total drive speed as F
so, to get that speed you take motor with two rotors.


F=F1+F2

P1 ~ F1^2+F2^2

P2 ~ (F1+F2)^2

Obviously P2>> P1


That means that two rotor motors are more suitable for high-speed application than single-rotor motors.

On that image F1=F2 = W

Total rotation speed is 2*W.

Hysteresis frequency is W.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/c318e031-84d3-47f6-837c-dd86074bad53" />


Simple winding for radial and axial two rotor motors.
For a described scheme we have 2 less power for hysteresis and 4 times less power for eddy current.

Most satisfying thing: 

You can connect motor in series.

So you will get 2*N*w speed 

and onle 2*N*w^2 hysteresis losses.

for the same speed you will get (2*N*w)^2= 4*N^2*w^2 losses

For seal connection of electric drives - 2*N*w^2

or  **(2*N) less losses for hysteresis and so on**.

Where N - number of electric drives connected in series.
