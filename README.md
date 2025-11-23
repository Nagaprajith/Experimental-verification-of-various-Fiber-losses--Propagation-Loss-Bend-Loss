# Experimental-verification-of-various-Fiber-losses--Propagation-Loss-Bend-Loss

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables  

**Theory:**  

~~~
Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km.
Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.
~~~
<img width="842" height="443" alt="image" src="https://github.com/user-attachments/assets/4074b1b0-67d3-4a56-b1ce-1771e95979b4" />

**Procedure:**  

~~~
	Connect the power supply with proper polarity to the kit link-B and switch it on.
	Keep all Switch Faults in OFF position.
	Keep switch SW8 towards TX position.
	Keep switch SW9 towards TX1 position.
	Keep Jumper JP5 towards +12V position.
	Keep Jumpers JP6, JP9, JP10 shorted.
	Keep Jumper JP8 towards sine position.
	Keep Intensity control pot P2 towards minimum position.
	Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.
~~~ 
<img width="743" height="301" alt="image" src="https://github.com/user-attachments/assets/27fc2ffa-31ae-41aa-b364-921928bf306e" />

~~~
	Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
	Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
	Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
	Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.
~~~
<img width="716" height="294" alt="image" src="https://github.com/user-attachments/assets/f12507f5-0ec1-4107-98ac-07438aa418e6" />

~~~
	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
~~~
<img width="446" height="183" alt="image" src="https://github.com/user-attachments/assets/41e15760-c4a5-459f-a72d-00a77145205c" />

~~~
	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]

Where
a = nepers/ Meter
L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm
	Keep switch SW9 towards TX2 position.
	Keep Jumper JP7 towards +12V position.
	Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
	Observe the detected signal at post ANALOG OUT on oscilloscope.
~~~
**Tabulation:**
![WhatsApp Image 2025-11-16 at 14 46 15_5564f345](https://github.com/user-attachments/assets/cbb94f2b-4291-4d30-a5ff-cd16fd5a75a7)
![WhatsApp Image 2025-11-16 at 14 46 28_b1c9fc49](https://github.com/user-attachments/assets/3a1a1d5d-cc52-44c8-a656-c55a8229f460)


### Propagation Loss

| Fiber Length | Input Amplitude (V) | Output Amplitude (V)   |
|--------------|---------------------|------------------------|
|     1m       |        5v           |          10v           |
|     0.5m     |        5v           |          14v           |

### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V)   |
|------------------|---------------------|------------------------|
|      3           |        5v           |           9v           |
|      5           |        5v           |           9.7v         |

**Result:**  
Attenuation and bending loss characteristics verified.

---
