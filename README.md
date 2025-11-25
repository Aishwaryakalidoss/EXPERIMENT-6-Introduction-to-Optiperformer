
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**
![Exp 6 Tabulation](https://github.com/user-attachments/assets/24418f4b-f4c7-4b59-85f7-a3a92648b860)


---

## Graphs

<img width="1051" height="379" alt="Screenshot 2025-11-25 102914" src="https://github.com/user-attachments/assets/edb564d9-e3cd-4437-9b56-1aa8383a5686" />


---

## RESULT

The OptiPerformer simulation successfully demonstrated how increasing fiber length causes reduced received power, degraded Q-factor, higher BER, and a progressively closing eye diagram in an optical communication system.
