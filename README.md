### Ex No: 01     Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools   

### Aim:
To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

### Tools Required:<br>
•	Personal Computer:<br>
•	Cadence Virtuoso Software:<br>

### S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window:<br>
2.	Type the following commands as follows and press enter.:<br>
•	csh:<br>
•	source /cadence/install/cshrc:<br>
•	virtuoso :<br>
### Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”:<br>
2.	Close the 2nd window:<br>
3.	Use 1st window i.e virtuoso window (CIW) for further processing.:<br>
i.	Create a New Library:<br>
ii.	Create Schematic Cell view.:<br>
iii.	Create the Symbol for schematic Cell view.:<br>
iv.	Create the test Cell view.:<br>
v.	Analog simulation by spectre:<br>


### i)	Procedure for Creating New Library.:<br>
•	File –New – Library:<br>
•	Name: Give name for ur library Ex: VLSILAB_EXP_1:<br>
•	Enable Attach to an existing technology library, Click OK:<br>
•	Attach the library to the technology library gpdk045.Click OK:<br>
### ii)	Create Schematic Cell view.:<br>
•	Go to 1st window i.e virtuoso (CIW):<br>
•	File-New-Cell view:<br>
•	Setup the new file form:<br>
	Library: Select the one you created.:<br>
	Cell: Give the experiment name Ex: Inverter ViewSchematic:<br>
	Type: Schematic press OK:<br>
•	Add the required components from the libraries and make the connections.:<br>
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances:<br>
	Click on browse. This opens the library browser:<br>
	Now select the appropriate library for components like :<br>
	Gpdk45 ------------------------nmos1v, pmos1v:<br>
	Create Input and Output pins:<br>
	Make the connections by using fixed narrow wire key:<br>
	Click Check and Save button:<br>
![image](![1](https://github.com/user-attachments/assets/5987c453-b1e9-4bd5-9316-ba97e395398f)


 
### iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute:<br> 
	Create – Cell view – From Cell view:<br>
	The cell view from cell view window appears:<br>
	Check Lib Name, Cell Name, From View name must be schematic Press ok:<br>
•	Now Symbol generation form appears. Click Ok If No changes required:<br>
•	A new window with with default symbol is created.:<br>
•	Edit the symbol if you want to give actual symbol shape else continue.:<br>
•	Execute Create-Cell view-from cell view:<br>
•	Library Name and Cell Name must be same which you have used for schematic. Press OK:<br>
•	Check for the position of pin side.Prss OK:<br>
•	Edit for the shape by Create-Shape-Choose required options to edit.:<br>

 ![Screenshot 2024-09-12 104421](https://github.com/user-attachments/assets/28a74f97-79fe-4e6c-a887-a91dfd0345af)



### iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view:<br>
	Setup the new file form:<br>
	Library: Select the one you created.:<br>
	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test:<br>
	View: Schematic:<br>
	Type: Schematic press OK:<br>
•	Follow the step 3(ii) d to make the required connections:
![Screenshot 2024-09-12 104451](https://github.com/user-attachments/assets/959aea13-c810-4d3d-9bb2-76cd5f227d9c)



 
Analog simulation by SPECTRE.
•	In test cell view window:<br>
•	Launch – ADE L(Analog Design Environment):<br>
	Execute Setup—Simulation/directory/Host A new window opens:<br>
	Set the simulation window to spectre and click ok:<br>
	Execute Analysis – Choose. A window opens.:<br>
	Select the type and set the specifications and press OK:<br>
	Execute Output s—to be plotted – Select on Schematic:<br>
	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse:<br>
•	Execute Simulation -- Net list and Run
 

For Transient Analysis Settings and Output
 
 
![Screenshot 2024-09-12 104753](https://github.com/user-attachments/assets/63df634a-c136-4bac-b7c1-fcf1a01319f4)


 ![Screenshot 2024-09-12 104645](https://github.com/user-attachments/assets/5acf03e5-8671-4dd2-a25b-5bbc7cc2ea6f)


 For DC Analysis Settings and Output
![Screenshot 2024-09-12 104753](https://github.com/user-attachments/assets/9c87657c-ac10-47d0-9b40-514564083138)


![Screenshot 2024-09-12 104802](https://github.com/user-attachments/assets/4f88c5d5-e04a-40ea-9e13-a66897973c84)


 




 

### Results:
1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.:<br>
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.:<br>
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











