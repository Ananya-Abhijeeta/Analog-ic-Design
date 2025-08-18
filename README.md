# Analog-ic-Design

Internship summary on designing analog ICs—covering topics like USB-MIDI microphone design, preamplifier design, transistor-level circuits, simulations via ngspice/xschem, PCB testing, and more.
This section explains the analog front-end of a USB microphone setup and its role in signal conditioning and conversion!


<img width="1120" height="542" alt="Screenshot 2025-08-18 193013" src="https://github.com/user-attachments/assets/60ca01e8-03dc-4961-9c69-ebde01eb2603" />


## Thevinin equivalent model of the microphone
<img width="1415" height="708" alt="image" src="https://github.com/user-attachments/assets/c9ae9615-3b44-43bc-9f12-913bad966530" />


**Frequency Response**
<img width="1600" height="659" alt="image" src="https://github.com/user-attachments/assets/1f6e50e5-a9d7-4725-8894-abf08ca53b02" />

**Simulink Output**
<img width="488" height="347" alt="image" src="https://github.com/user-attachments/assets/06a20313-8821-4b8e-a799-315b99aa60ad" />
**Highpass filter using the opamp**
<img width="2138" height="1731" alt="image" src="https://github.com/user-attachments/assets/5a178dc7-28fa-4f51-9bcf-c14e440a626d" />
***Siliwiz simulation***
![SILWIZ](https://github.com/user-attachments/assets/07681676-a6fd-4627-9134-3fa203636be2)
***Current Mirror***
![Circuit 1](https://github.com/user-attachments/assets/0d4c933b-2988-44b6-8f90-595b1ee7f4c0)
## Output##
**Verified three modes of operation: cutoff, triode, and saturation.

Visualized how VGS modulates drain current.

Confirmed square-law relationship in saturation (linear √ID vs VGS).

Demonstrated log-linear behavior in subthreshold region.

Learned to interpret raw Ngspice waveforms for device-level analysis**









