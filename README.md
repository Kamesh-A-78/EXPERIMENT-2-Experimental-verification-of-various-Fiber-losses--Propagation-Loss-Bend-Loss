# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

**Theory:**  
Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km.
Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.
 <img width="842" height="443" alt="image" src="https://github.com/user-attachments/assets/529a7e9b-5596-48a5-8ff9-27976f8a37b0" />


**Procedure:**  
	Connect the power supply with proper polarity to the kit link-B and switch it on.
	Keep all Switch Faults in OFF position.
	Keep switch SW8 towards TX position.
	Keep switch SW9 towards TX1 position.
	Keep Jumper JP5 towards +12V position.
	Keep Jumpers JP6, JP9, JP10 shorted.
	Keep Jumper JP8 towards sine position.
	Keep Intensity control pot P2 towards minimum position.
	Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.

<img width="743" height="301" alt="image" src="https://github.com/user-attachments/assets/b2c2fdf2-a382-436a-bab1-68bcca6aa0cb" />


	Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
	Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
	Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
	Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.
<img width="716" height="294" alt="image" src="https://github.com/user-attachments/assets/3b26e22d-e411-4049-9cb8-88eed5389e6a" />


	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
 
 
<img width="696" height="286" alt="image" src="https://github.com/user-attachments/assets/390fe723-e1e0-4b43-98e0-d3a0dfecf26f" />


	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]

Where
a = nepers/ Meter
L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm
	Keep switch SW9 towards TX2 position.
	Keep Jumper JP7 towards +12V position.
	Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
	Observe the detected signal at post ANALOG OUT on oscilloscope.

<img width="829" height="342" alt="image" src="https://github.com/user-attachments/assets/4ad2b275-324c-4cc5-adb4-172548272bf8" />


	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
Where
a = nepers/ Meter
L1 = Fiber Length for V1 ; L2 = Fiber Length for V2 This a is for peak wavelength of 950nm
	Compare the two a values.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/32c7c1cb-395a-414e-92be-e86b122c7977" />

**Tabulation:**
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/e02f2241-eb42-4ff6-9b5d-8fc23d5f9192" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/21ad4045-bd45-4ecc-a5c9-15c5f50e4eeb" />



### Propagation Loss

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|              |                     |                        |

### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
|                  |                     |                        |

**Result:**  
Attenuation and bending loss characteristics verified.

---
