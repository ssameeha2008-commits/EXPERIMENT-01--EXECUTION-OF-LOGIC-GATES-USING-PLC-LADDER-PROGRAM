<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/d13c1ef3-5b93-4bff-8157-7094f888bded" /># EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :Sameeha S
 # REGISTER NUMBER :212225230243
 # DEPARTMENT AIDS
 # YEAR II
 # DATE 20-07-2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
### AND GATE:
<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/60b531c0-955f-48d9-b113-e9cc6a9db92f" />

### OR GATE:
<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/e253b0aa-cd14-4902-a105-5e689c985909" />

### NOT GATE:
<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/2a9d1ffb-43c2-4cde-8e7f-1e12c701605a" />

### NAND GATE:
<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/e96ab2c7-1d9b-4364-a7b5-4856f27f9cd2" />

### NOR GATE:
<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/677e6809-c543-48dd-a866-62bac2962c2c" />


### XOR GATE:
<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/1d2967f7-df63-49bf-bf90-899c80c211ba" />



 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
### AND GATE
<img width="700" height="125" alt="image" src="https://github.com/user-attachments/assets/0cba4a02-2b63-4ede-bd92-675d2983ec6c" />

### OR GATE
<img width="701" height="209" alt="image" src="https://github.com/user-attachments/assets/9f62a1a5-6901-41d8-8c44-08626737ce81" />

### NOT GATE
<img width="645" height="141" alt="image" src="https://github.com/user-attachments/assets/c6b2b811-5dc7-4b1b-b316-56ecece8cdc2" />

### NAND GATE
<img width="667" height="130" alt="image" src="https://github.com/user-attachments/assets/181da58c-7f8e-47cc-9789-6c7751c6d10a" />

### NOR GATE
<img width="665" height="134" alt="image" src="https://github.com/user-attachments/assets/04a61c69-1ccf-4103-8a6c-bd3916788fba" />

### XOR GATE
<img width="683" height="246" alt="image" src="https://github.com/user-attachments/assets/f45ed319-ec7a-40b6-89ed-bb31ad428512" />

### DEVICE MONITOR TABLE:
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/71d2f8b5-02a5-4247-9118-4de5026afc57" />
<img width="1916" height="1019" alt="image" src="https://github.com/user-attachments/assets/75e4bef8-ae84-46af-baa9-700dad3dcf74" />
<img width="1906" height="995" alt="image" src="https://github.com/user-attachments/assets/6e30de1d-5d0e-4280-967b-de0b79c0035a" />
<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/1eecece4-4dc7-4faa-a4f6-8e0a27dd93e8" />



### Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
