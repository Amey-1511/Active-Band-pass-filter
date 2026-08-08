#  Band-Pass Filter (Active Filter)

<p align="center">
  <b>Design and simulation of a second-order active band-pass filter using LTspice</b>
</p>

---

## 📌 Overview
This project involves the design, analysis, and simulation of a Second-Order Active Band-Pass Filter using an Operational Amplifier (Op-Amp). The filter is designed to pass signals within a specific frequency range while attenuating frequencies outside the desired passband.

The complete circuit was designed and simulated using LTspice, with the frequency response analyzed through AC sweep simulation.

---

## ⚙️ Circuit Description
The circuit is implemented using an operational amplifier to achieve an **active band-pass response**.

It is designed to:
- Reject low-frequency signals  
- Pass mid-frequency signals  
- Attenuate high-frequency signals  

---

## 🧪 Simulation Details
- **Software:** LTspice  
- **Analysis:** AC Sweep (.ac dec)  
- **Frequency Range:** 1 kHz – 10 kHz  

---

## 🧮 Design Methodology 
The following steps were followed for designing the filter: 
1. Define the required passband and center frequency.
2.  Select suitable resistor and capacitor values.
3. Calculate the theoretical cutoff frequencies.
4.  Design the second-order active band-pass filter.
5. Implement the circuit in **LTspice**.
6.  Perform an **AC Sweep Analysis**.
7.  Obtain the magnitude and phase response.
8.  Determine the lower and upper cutoff frequencies from the simulation.
9. Calculate the center frequency, bandwidth, and quality factor.
10. Compare theoretical and simulated results.
 ---

## 📈 Frequency Response 
The simulated filter exhibits the expected **second-order band-pass response**.
- Frequencies below the lower cutoff frequency are attenuated.
-  Frequencies around the center frequency experience maximum gain.
-  Frequencies above the upper cutoff frequency are attenuated. The Bode plot obtained from LTspice can be used to identify the cutoff frequencies and analyze the overall filter performance. ---
## 📊 Observations
- Output is low at low frequencies  
- Maximum gain occurs in mid-frequency range  
- Output decreases at high frequencies  
- Clear band-pass response is observed  

---

## 🎯 Applications
- Audio filtering  
- Communication systems  
- Signal processing  

---

## 📂 Project Files
- LTspice simulation file (.asc)  
- Project report (DOCX)  
- Circuit and waveform images  
- Design notes  

---

## 📚 Reference
R. L. Boylestad and L. Nashelsky, *Electronic Devices and Circuit Theory*, 11th ed., Pearson, 2013.

---

## 🧑‍💻 Author
**Amey Chauhan**  
B.Tech - Electrical engineering
IIT ROPAR

