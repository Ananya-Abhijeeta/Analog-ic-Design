# Analog-ic-Design

Internship summary on designing analog ICs—covering topics like USB-MIDI microphone design, preamplifier design, transistor-level circuits, simulations via ngspice/xschem, PCB testing, and more.
This section explains the analog front-end of a USB microphone setup and its role in signal conditioning and conversion!


<img width="1120" height="542" alt="Screenshot 2025-08-18 193013" src="https://github.com/user-attachments/assets/60ca01e8-03dc-4961-9c69-ebde01eb2603" />


## Thevinin equivalent model of the microphone
<img width="1415" height="708" alt="image" src="https://github.com/user-attachments/assets/c9ae9615-3b44-43bc-9f12-913bad966530" />


<img width="2159" height="2289" alt="image" src="https://github.com/user-attachments/assets/e8a5c3f8-475d-46d0-89e1-88e800a90abf" />



**Frequency Response**
<img width="1600" height="659" alt="image" src="https://github.com/user-attachments/assets/1f6e50e5-a9d7-4725-8894-abf08ca53b02" />

**Simulink Output**
<img width="488" height="347" alt="image" src="https://github.com/user-attachments/assets/06a20313-8821-4b8e-a799-315b99aa60ad" />
**Highpass filter using the opamp**
<img width="2138" height="1731" alt="image" src="https://github.com/user-attachments/assets/5a178dc7-28fa-4f51-9bcf-c14e440a626d" />
<img width="2159" height="2289" alt="image" src="https://github.com/user-attachments/assets/736a2c65-3647-4545-802a-cd32b48f4aca" />

***Siliwiz simulation***
![SILWIZ](https://github.com/user-attachments/assets/07681676-a6fd-4627-9134-3fa203636be2)
***Current Mirror***
![Circuit 1](https://github.com/user-attachments/assets/0d4c933b-2988-44b6-8f90-595b1ee7f4c0)
**Schematic of opamp model**
<img width="1848" height="872" alt="image" src="https://github.com/user-attachments/assets/a405190e-0c58-471d-b670-e2732e55eabb" />
**Symbol of opamp model**
<img width="763" height="577" alt="image" src="https://github.com/user-attachments/assets/7b8bcfd5-2af6-4576-a448-d7c1515631f6" />
**Simple RC High Pass Filter**
<img width="1918" height="1025" alt="image" src="https://github.com/user-attachments/assets/eddaec06-abe6-40b5-b966-4f34ede7764d" />
**Current Mirror Circuit**
<img width="1693" height="880" alt="image" src="https://github.com/user-attachments/assets/e81cdba8-92b0-4e5a-9a1a-b288d15e9465" />
**Small Signal Analysis**
<img width="1896" height="876" alt="image" src="https://github.com/user-attachments/assets/c8eebe85-efad-4e14-b0c6-00661968001f" />
Waveform of MEMS Microphone
<img width="4160" height="3112" alt="image" src="https://github.com/user-attachments/assets/3cc74579-9a15-4885-8d0b-93a12d3dc407" />








## Output
Verified three modes of operation: cutoff, triode, and saturation.

Visualized how VGS modulates drain current.

Confirmed square-law relationship in saturation (linear √ID vs VGS).

Demonstrated log-linear behavior in subthreshold region.

Learned to interpret raw Ngspice waveforms for device-level analysis









