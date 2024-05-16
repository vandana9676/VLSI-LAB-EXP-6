# VLSI-LAB-EXP-6
SIMULATE AND SYNTHESIS INVERTER USING CADENCE
## AIM: 
To create,simulate the design of CMOS inverter,NAND,NOR from schematic using cadence.

## APPARATUS REQUIRED:

cadence

PROCEDURE:

## Commands to get into Cadence
Right Click and open the terminal window
Type the following commands as follows and press enter. i) tcsh ii) source /home/install/cshrc iii) virtuoso
## Procedure for Schematic simulation using Cadence
Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing. i) Create a New Library ii) Create Schematic Cell view. iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view. v) Analog simulation by spectre
## Procedure for Creating New Library.
a) File –New – Library b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK c) Attach the library to the technology library gpdk045.Click OK

## Create Schematic Cell view.
a) Go to 1st window i.e virtuoso(CIW) b) File-New-Cell view c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic d) Type: Schematic press OK e) Add the required components from the libraries and make the connections. f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin h) Make the connections by using fixed narrow wire key i) Click Check and Save button

## Creating the Symbol for schematic Cell view
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now Symbol generation form appears. Click Ok If No changes required c. A new window with with default symbol is created. d. Edit the symbol if you want to give actual symbol shape else continue. i. Execute Create-Cell view-from cell view ii. Library Name and Cell Name must be same which you have used for schematic. Press OK iii. Check for the position of pin side.Prss OK iv. Edit for the shape by Create-Shape-Choose required options to edit.

## Creating the new test cell view
a) Go to CIW window, Execute File-New-Cell view b) Setup the new file form Library: Select the one you a created. Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test View: Schematic Type: Schematic press OK

## Analog simulation by SPECTRE.
a. In test cell view window i. Launch – ADE L(Analog Design Environment) b. Execute Setup—Simulation/directory/Host A new window opens c. Set the simulation window to spectre and click ok d. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK. e. Execute Analysis – Choose. A window opens. f. Select the type and set the specifications and press OK g. Execute Output s—to be plotted – Select on Schematic h. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse i. Execute Simulation -- Net list and Run

## INVERTER SCHEMATIC:
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/a4113e90-8977-48a3-a747-5d22253d3f1c)
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/42ebc1e7-ffa5-42d5-b8bc-35ec46b34e90)

Specifications: Vpulse

V1 = 0	       

V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Vdc = 1
Simulation Settings

Setup for transient analysis:

Stop time =400n

Setup for D.C analysis

Component to be selected in schematic is for d.c analysis

Start = -1 Stop = 1 resp.
Expected Waveform:

Transient Analysis:
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/63d4b36d-8111-437f-b327-f2602cae9661)
DC Analysis:
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/59ff680b-f241-4d06-a0ba-05df6a372acb)
NAND SCHEMATIC :

![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/7a3aecaf-32e9-40ba-ab33-1e66655621ab)
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/3e3a7d69-f1cf-48c1-9132-80ecd33e635f)

Specifications:

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

Transient Analysis:
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/e1ce8ba1-97ed-4702-87d4-68f86c6b2e70)
NOR SCHEMATIC:

![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/003b5167-7730-44c0-ad03-7b0415b0ce29)

![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/f0bfb458-4039-4006-a250-8114e5d372de)
Specifications:

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

Transient Analysis:
![image](https://github.com/vandana9676/VLSI-LAB-EXP-6/assets/165563035/45ff3b97-97fa-4668-8743-240e830478ab)
RESULT:

Thus, the design,simulation and verification of the CMOS inverter,NAND,NOR from schematic using cadence was successfully completed.
