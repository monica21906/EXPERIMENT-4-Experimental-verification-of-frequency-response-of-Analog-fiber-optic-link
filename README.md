
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

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

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
