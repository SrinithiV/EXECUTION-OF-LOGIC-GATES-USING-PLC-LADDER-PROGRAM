# EXPERIMENT.NO:1
# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM

 # NAME : SRINITHI V
 # REGISTER NUMBER : 212222110046
 # DEPARTMENT : CSE(IoT)
 # YEAR : III
 
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
## AND Gate:
| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   1    |

## OR Gate:
| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   1    |

## NOT Gate:
| Input | Output |
|-------|--------|
|   0   |   1    |
|   1   |   0    |

## NAND Gate:
| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |

## NOR Gate:
| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   0    |

## XOR Gate:
| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |

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


# SIMULATION RESULTS:
## AND Gate:
![AND](https://github.com/user-attachments/assets/eb21c53c-dc22-4755-89d8-bdccd953eeac)
## OR Gate:
![OR](https://github.com/user-attachments/assets/42d78280-9cb7-463c-8c55-3db58a6b252e)
## NOT Gate:
![NOT](https://github.com/user-attachments/assets/ec3c071d-466c-4839-a03b-ffb509a1ac31)
## NAND Gate:
![NAND](https://github.com/user-attachments/assets/1cbef49f-908d-4a33-8e90-543ea6001102)
## NOR Gate:
![NOR](https://github.com/user-attachments/assets/3bba9280-16c9-4d6b-a2c1-0d7b382e68c9)
## XOR Gate:
![XOR](https://github.com/user-attachments/assets/c7345af9-4251-46df-9af2-eef7f8966b21)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
