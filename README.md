📻 FM Receiver Using TDA7000 IC

A compact and low-cost FM Receiver capable of receiving 88–108 MHz radio signals using the TDA7000 FM Receiver IC and LM386 Audio Amplifier.

📌 Project Description

This project demonstrates the design and implementation of an FM Receiver using the TDA7000 IC. The receiver captures FM broadcast signals, selects the desired station using an LC tuning network, demodulates the FM signal, amplifies the recovered audio using the LM386 amplifier, and outputs sound through a speaker.

The project was designed and simulated using Proteus and focuses on understanding RF amplification, FM demodulation, tuning circuits, and audio amplification.


| **Component**                              | **Purpose / Function**                                                            |
| ------------------------------------------ | --------------------------------------------------------------------------------- |
| **TDA7000 FM Receiver IC**                 | Receives, demodulates, and processes FM radio signals.                            |
| **LM386 Audio Amplifier IC**               | Amplifies the recovered audio signal to drive the speaker.                        |
| **BF494 / BC547 Transistor**               | Amplifies weak RF signals received from the antenna.                              |
| **Inductor (Coil)**                        | Forms the LC tuning circuit to select the desired FM station.                     |
| **Variable Capacitor / Trimmer Capacitor** | Tunes the resonant frequency of the LC circuit for station selection.             |
| **Resistors**                              | Provide biasing, current limiting, and voltage division within the circuit.       |
| **Capacitors**                             | Used for coupling, decoupling, filtering, and frequency stabilization.            |
| **Electrolytic Capacitors**                | Filter power supply noise and improve audio signal quality.                       |
| **Antenna**                                | Receives FM broadcast signals from the air.                                       |
| **8Ω Speaker**                             | Converts the amplified electrical audio signal into sound.                        |
| **Power Supply (5V/9V)**                   | Provides operating voltage to the receiver and amplifier circuits.                |
| **PCB / Breadboard**                       | Serves as the platform for assembling and interconnecting the circuit components. |

🖼 Block Diagram

![Block Diagram](<img width="1691" height="930" alt="ChatGPT Image Jul 7, 2026, 11_57_07 PM" src="https://github.com/user-attachments/assets/b3f9a7e7-f2ac-4b9b-b641-73b5011fb3a9" />
)




🖼 Circuit Diagram

<img width="1370" height="961" alt="WhatsApp Image 2026-04-22 at 10 42 57 PM" src="https://github.com/user-attachments/assets/5fdf2a7b-2fbb-434e-ad11-d27541ae71e7" />

<p align="center">

</p>



📁 Repository Structure
FM-Receiver-TDA7000/
│── README.md
│docs/
├── block_diagram.png
├── circuit_diagram.png
├── hardware_setup.jpg
├── output.jpg
└── project_report.pdf
│── Proteus/
│   ├── FM_Receiver.pdsprj
│   └── FM_Receiver.dsn
│── Images/
│   ├── hardware.jpg
│   ├── output.jpg
│   └── pcb.jpg


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

📷 Project Images
Circuit Diagram

Insert image here

Hardware Setup

Insert image here

Output

Insert image here

📖 Learning Outcomes
FM communication
RF amplification
Resonance and LC tuning
FM demodulation
Audio amplification
Analog communication systems
Proteus simulation

