🔹 I’m excited to share my Verilog project journey into digital arbitration and data prioritization! This project focuses on designing and simulating three fundamental digital components: Priority Encoder, Fixed Priority Arbiter, and Round Robin Arbiter — all developed and verified using Icarus Verilog and GTKWave and EDA playground tools.

These modules are key for managing requests in digital systems like buses, communication protocols, and multiprocessor environments — ensuring fairness, speed, and efficiency.

🔗 linked in : https://www.linkedin.com/in/arun-u1809ajs

PROJECT OVERVIEW
🟦 Priority Encoder: A combinational circuit that detects the highest-priority active input among multiple request lines and outputs its binary index. Useful in interrupt handling and priority-based resource allocation.

🟦 Fixed Priority Arbiter (FPA): A sequential circuit that always grants access to the highest-priority request in a predefined fixed order. Simple but may lead to starvation of lower-priority inputs.

🟦 Round Robin Arbiter (RRA): A sequential arbiter that cycles through requests in a rotating order, ensuring fair access by giving each requestor a turn. Solves starvation issues present in fixed schemes.

TECHNICAL FEATURES

▪️ Designed using Verilog HDL, simulated with Icarus Verilog + GTKWave
▪️ Implemented both combinational (Priority Encoder) and sequential FSM-based logic (Arbiters)
▪️ Clock and reset-controlled operations for robust testing
▪️ Validated through waveform analysis to ensure expected arbitration behavior
▪️ Testbenches created to simulate all possible request scenarios

APPLICATIONS & USE CASES

✅ Bus Arbitration: Managing multiple masters in systems like AMBA, AXI
✅ Interrupt Controllers: Handling CPU interrupt lines based on priority
✅ Network Routers & Multiprocessors: Resolving packet access or core communication
✅ Embedded Systems: Ensuring efficient and fair access to shared peripherals

This project deeply enhanced my understanding of digital arbitration, finite state machines, priority encoding, and fairness in system-level communication. It also gave me strong hands-on exposure to Verilog simulation and waveform debugging — a big step towards my chip design goals.

#Verilog #DigitalDesign #Arbiter #PriorityEncoder #RTLDesign #ICDesign #FPGA #IcarusVerilog #GTKWAVE #HardwareDesign #ChipDesign #GitHub #SVNIT #ECE #VLSI
