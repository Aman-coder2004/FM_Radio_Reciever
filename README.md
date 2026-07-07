📻 FM Receiver Using TDA7000 IC

A compact and low-cost FM Receiver capable of receiving 88–108 MHz radio signals using the TDA7000 FM Receiver IC and LM386 Audio Amplifier.

📌 Project Description

This project demonstrates the design and implementation of an FM Receiver using the TDA7000 IC. The receiver captures FM broadcast signals, selects the desired station using an LC tuning network, demodulates the FM signal, amplifies the recovered audio using the LM386 amplifier, and outputs sound through a speaker.

The project was designed and simulated using Proteus and focuses on understanding RF amplification, FM demodulation, tuning circuits, and audio amplification.

🎯 Objectives
Design a low-cost FM receiver.
Receive FM signals in the 88–108 MHz band.
Tune different FM stations using an LC resonant circuit.
Recover the transmitted audio signal.
Amplify the audio using LM386.
Produce clear sound through a speaker.
🛠 Components Required
Component	Specification	Quantity
TDA7000 IC	FM Receiver IC	1
LM386 IC	Audio Amplifier	1
BF494 / BC547 Transistor	RF Amplifier	1
Variable Capacitor / Potentiometer	Frequency tuning	1
Inductor (LC Tank)	RF Tuning	1
Capacitors	Various values	As required
Resistors	Various values	As required
Speaker	8Ω	1
Antenna	Copper wire	1
5V Supply	TDA7000	1
9V Battery	LM386	1
⚙ Working Principle
1. Antenna

The antenna receives FM radio signals from nearby broadcasting stations.

↓

2. RF Amplifier

The received weak RF signal is amplified using a transistor (BF494/BC547).

↓

3. LC Tuning Circuit

The LC resonant circuit selects one station from the 88–108 MHz FM band while rejecting unwanted frequencies.

↓

4. TDA7000 FM Receiver IC

The IC performs

Frequency conversion
Intermediate frequency processing
FM demodulation
Audio signal recovery

↓

5. LM386 Audio Amplifier

The recovered audio signal is amplified to drive the speaker.

↓

6. Speaker

Produces audible sound from the amplified electrical signal.

🔄 Block Diagram
        Antenna
           │
           ▼
     RF Amplifier
           │
           ▼
      LC Tuning Circuit
           │
           ▼
      TDA7000 Receiver
           │
           ▼
      LM386 Amplifier
           │
           ▼
         Speaker
🖼 Circuit Diagram

Replace the placeholder below with the circuit image.

docs/
   circuit_diagram.png
<p align="center">

Circuit Diagram

</p>

Save the circuit diagram from your report as docs/circuit_diagram.png.

📁 Repository Structure
FM-Receiver-TDA7000/
│
├── README.md
├── LICENSE
├── docs/
│   ├── circuit_diagram.png
│   ├── block_diagram.png
│   └── project_report.pdf
│
├── Proteus/
│   ├── FM_Receiver.pdsprj
│   └── FM_Receiver.dsn
│
└── Images/
    ├── setup.jpg
    ├── output.jpg
    └── pcb.jpg
✨ Features
FM Band (88–108 MHz)
Simple and low-cost design
Compact hardware
High sensitivity
Good audio quality
Easy tuning
Suitable for educational purposes
📚 Applications
Educational electronics projects
Communication laboratories
RF learning
Embedded systems projects
Hobby radio receiver
Analog electronics demonstrations
🚀 Future Improvements
Digital frequency display
Automatic station scanning
Stereo FM reception
PCB implementation
Better RF filtering
Battery-powered portable design
🧪 Software Used
Proteus Design Suite
Microsoft Word (Documentation)
📷 Project Images
Circuit Diagram

Insert image here

Hardware Setup

Insert image here

Output

Insert image here

📖 Learning Outcomes

After completing this project, one can understand:

FM communication
RF amplification
Resonance and LC tuning
FM demodulation
Audio amplification
Analog communication systems
Proteus simulation
📜 License

This project is intended for educational purposes.
