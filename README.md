# Download

VERSION: BETA v9.0

DONWLOAD LINK: https://drive.google.com/drive/folders/18MdogcQEW1887eT0yU7Oh_MuqxNseY25

Instructions: 
1. Download the whole folder "circuit_simulation_beta_v7.0" (it will be downloaded as zip)
2. Extract the downloaded zip file.
3. Open the extracted folder and open "circuit_simulation_beta_v7.0"
4. Run the "Physics_Simulation_Beta_v7.0" application or executable file. Choose the executable file not the pck file.

# Circuit Simulation
Made with Godot Game Engine and SPICE using Pyspice

CONTROLS:
- Creating wire - can be simply connected using component terminal to another component terminal (for example, Battery positive terminal to either of the two terminals of resistor). For more complex connections, such as in a parallel or combined circuit, use nodes.
- Delete components:
  - for wires, click the wire then press the "Del" key
  - for other objects, click the object then press the "Del" key. For objects with custom behaviors such as switch and nodes, drag the object first by holding the left mouse button, then press Del.
  - When drawing a wire before connecting it, CTRL + Z keys or "Del" key can dismiss wire drawing.
- How to connect/disconnect the switch:
  - Connecting the switch: Drag the switch where the mouse is hovering the wire. It is hovering the wire when the wire turns blue. Then press E.
  - Disconnecting the switch: Hold left mouse button to the switch, then press E.
- Movement:
  - Hold the scroll wheel to pan and scroll up or down for zooming. 

COMPONENTS:
- Node - To connect three or more components together. This is used for making more complex connections.
- Reference node - Serves as the reference voltage (in 0 volts) in the circuit. Used for complex circuits.
- Battery - DC voltage source, 9 volts by default.
- Resistor - 1 kiloOhms by default.
- Power supply - AC voltage source, 220 volts by default.
- Capacitor - For AC. 0.001 Farad by default. WORK IN PROGRESS
- Inductor - For AC. 0.001 Henry by default. WORK IN PROGRESS
- Ground - The ground node

FEATURES:
- Popups - Can show how values change when simulation runs. Can be disabled.
- Properties - For changing component values and prefix units used for values.

SCOPE:
- Ohm's law
- Kirchoff's current law
- Kirchoff's voltage law
- AC circuit. WORK IN PROGRESS
- DC circuit
- Light bulb simulation
- circuit with switches

Report bugs here: TBA
