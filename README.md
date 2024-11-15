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

The Available technology nodes are 180nm ,90nm and 45nm.

In the terminal, initialise the tools with the following commands if a new terminal is being used.

csh
source /cadence/install/cshrc




The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.
Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![Screenshot (26)](https://github.com/user-attachments/assets/97a9fdaf-e128-4533-a3d1-f33c1f2cde51)

Area report:

![Screenshot (59)](https://github.com/user-attachments/assets/c1eaf783-22f1-44c1-9fdf-eead32589a95)<br>
<br><br>


Power Report:

![Screenshot (41)](https://github.com/user-attachments/assets/1f1130a4-5043-4110-9f87-83d2b1f64ed5)<br>

Timing Report:
![Screenshot (57)](https://github.com/user-attachments/assets/353c401a-c7ae-4e64-9759-7fe21fea4109)<br>


Result:
The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
