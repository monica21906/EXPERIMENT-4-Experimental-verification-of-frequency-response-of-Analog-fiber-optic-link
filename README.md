
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter module takes the input signal in electrical form and then transforms it into optical (light) energy containing the same information. The optical fiber is the medium which takes the energy to the receiver. At the receiver light is converted back into electrical form with the same pattern as originally fed to the transmitter.

TRANSMITTER:

Fiber Optic transmitters are typically composed of a buffer, driver and Optical Source. The buffer electronics provides both an electrical connection and isolation between the transmitter and the electrical system supplying the data. The driver electronics provides electrical power to the Optical source in a fashion that duplicates the pattern of data being fed to the transmitter. Finally the optical source (LED) converts the electrical current to light energy with the same pattern. The LED SFH450V (950nm) supplied with this kit operates outside the visible light spectrum. Its Optical output is centered at near infrared wavelength of 950nm. The LED SFH756V (660nm) supplied with this kit operates at the visible light spectrum. Its Optical output is centered at wavelength of 660nm.

RECEIVER:

The function of the receiver is to convert the optical energy into electrical form, which is then conditioned to reproduce the transmitted electrical signal in it's original form. The detector SFH350V (Photo Transistor Detector) used in the kit has a transistor type output. The parameters usually considered in the case of detector are it's responsivity at peak wavelength and response time. SFH350V (Photo Transistor Detector) has responsivity of about 0.8mA/10uW at 660nm. But its response time is quite large and thus has lower bandwidth of about 300 KHz. When optical signal falls on the base of the transistor detector, proportional current flows through its emitter generating the voltage across the resistance connected between emitter and ground. This voltage is the duplication of the transmitted electrical signal, which can be amplified.

---

## PROCEDURE

 Refer to the block diagram & carry out the following connections and settings.

▪ Connect the power supply with proper polarity to the kit link-B and switch it on.

▪ Keep all Switch Faults in OFF position.

▪ Keep switch SW8 towards TX position.

▪ Keep switch SW9 towards TX1 position.

▪ Keep Jumper JP5 towards +12V position.
<img width="532" height="247" alt="image" src="https://github.com/user-attachments/assets/441834c8-3f2d-4cc7-98cf-873d39446e08" />
▪ Keep Jumpers JP6, JP9, JP10 shorted.

▪ Keep Jumper JP8 towards sine position.

▪ Keep Intensity control pot P2 towards minimum position.

▪ Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.

▪ Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.

▪ Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
<img width="573" height="230" alt="image" src="https://github.com/user-attachments/assets/d2054527-cd33-447e-ab79-70ef813a5c72" />
 Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.

▪ Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

▪ To measure the analog bandwidths of the phototransistor vary the input signal frequency and observe the detected signal at various frequencies.

▪ Plot the detected signal against applied signal frequency and from the plot determine the 3dB down frequency.

▪ Keep switch SW9 towards TX2 position.

▪ Keep Jumper JP7 towards +12V position.

▪ Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.

▪ Observe the detected signal at post ANALOG OUT on oscilloscope.
<img width="576" height="267" alt="image" src="https://github.com/user-attachments/assets/0292fd01-507f-4a13-ad05-9e8652c21f8f" />




---

## BLOCK DIAGRAM

<img width="527" height="222" alt="image" src="https://github.com/user-attachments/assets/bb7cdd3c-0c96-4c90-bd3e-0464f3f28f04" />


---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="571" height="122" alt="image" src="https://github.com/user-attachments/assets/50281445-d044-48e2-809a-f65bd0f2eb65" />


---

## TABULATION  
**Transmission through Analog Link**

![WhatsApp Image 2025-11-18 at 14 28 49_a558dc50](https://github.com/user-attachments/assets/ea280b11-3042-43c9-b0c4-44923306974c)

---

## MODEL GRAPH

<img width="721" height="308" alt="image" src="https://github.com/user-attachments/assets/01a5a04a-c230-4511-b52a-cf4de3f19e94" />


![WhatsApp Image 2025-11-18 at 14 30 36_c9db0340](https://github.com/user-attachments/assets/093541f5-0b67-4f74-8818-aba275ddfb43)

---

## RESULT
The transmitted and received waveforms for the 660 nm fiber link matched closely, confirming faithful analog and digital signal transfer. Output amplitude decreased with increasing frequency, showing the fiber link’s frequency-dependent response. The calculated –3 dB point confirms the bandwidth of the 660 nm analog/digital fiber optic link.
