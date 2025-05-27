# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2025-05-27 at 11 01 44_64ed53f3](https://github.com/user-attachments/assets/50213b29-4f10-477c-8797-4e5ef0ed08a9)


Area report:
![WhatsApp Image 2025-05-27 at 11 01 44_43af8a2c](https://github.com/user-attachments/assets/1a7e272d-de43-42e0-91cf-21a608a6cf1c)


Power Report:
![WhatsApp Image 2025-05-27 at 11 01 43_38049ea4](https://github.com/user-attachments/assets/4bc57db4-e182-46a0-ac18-6ba1609c07bd)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
