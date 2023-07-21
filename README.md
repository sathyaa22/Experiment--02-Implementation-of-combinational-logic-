### Name: Rahul V
### Registration no:23006860
# Experiment--02-Implementation-of-combinational-logic
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 
## Equipments Required:
 Hardware – PCs, Cyclone II , USB flasher
 Software – Quartus prime
## Theory:
 A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.

## Procedure:
1. Create a New Project:
   - Open Quartus and create a new project by selecting "File" > "New Project Wizard."
   - Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2. Create a New Design File:
   - Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
   - Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3. Write the Combinational Logic Code:
   - Open the newly created Verilog or VHDL file and write the code for your combinational logic.
     
4. Compile the Project:
   - To compile the project, click on "Processing" > "Start Compilation" in the menu.
   - Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5. Analyze and Fix Errors:*
   - If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
   - Review and fix any issues in your code if necessary.
   - View the RTL diagram.

6.*Verification:
   - Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
   - Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
   - Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform.
## Program:
![Screenshot (15)](https://github.com/23006860/Experiment--02-Implementation-of-combinational-logic-/assets/139841752/5559e363-c858-4bdc-948b-8ac2cf11ecaa)

## RTL realization
![Screenshot (9)](https://github.com/23006860/Experiment--02-Implementation-of-combinational-logic-/assets/139841752/ddc362d3-7840-4c4b-8af2-6e06b3c5196f)
## Truth Table:
![image](https://github.com/23006860/Experiment--02-Implementation-of-combinational-logic-/assets/139841752/aa5296ba-a8c1-4626-bc90-4bf85dfad195)


## Output waveform:
![Screenshot 2023-07-20 093600](https://github.com/23006860/Experiment--02-Implementation-of-combinational-logic-/assets/139841752/a9163aec-8fbf-40a5-9ef8-85a02454dfab)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
