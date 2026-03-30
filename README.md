# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: ARHAM S
# REGISTER NUMBER: 21222110005
# DEPARTMENT: CSE(IOT)
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
### ADDITION
<img width="774" height="234" alt="Screenshot 2026-02-23 104700" src="https://github.com/user-attachments/assets/11b32d3e-4a13-4d70-ba79-12925ef04013" />

### SUBTRACTION
<img width="759" height="239" alt="Screenshot 2026-02-23 104708" src="https://github.com/user-attachments/assets/561aa179-14be-430f-a380-9481db34f342" />

### MULTIPLICATION
<img width="785" height="235" alt="Screenshot 2026-02-23 104721" src="https://github.com/user-attachments/assets/b0e9589f-3a34-4ac5-951a-9981ccbd8481" />

### DIVISION
<img width="790" height="234" alt="Screenshot 2026-02-23 104728" src="https://github.com/user-attachments/assets/392a0191-5766-462b-998a-7d2d58ff5a22" />

### OR
<img width="784" height="235" alt="Screenshot 2026-02-23 104748" src="https://github.com/user-attachments/assets/4fc0edad-f82b-4526-8c5d-f8352977d892" />

### AND
<img width="776" height="235" alt="Screenshot 2026-02-23 104756" src="https://github.com/user-attachments/assets/1665675f-af43-49c7-a1f2-d114455eae02" />


### XOR
<img width="827" height="242" alt="Screenshot 2026-02-23 104804" src="https://github.com/user-attachments/assets/98862d5d-76d7-4f2f-97b1-7bcc0eb28520" />

### NEGATIVE(NOT)
<img width="714" height="181" alt="Screenshot 2026-02-23 104813" src="https://github.com/user-attachments/assets/410cd42c-9137-4269-a17e-8838471682ed" />


### DECREMENT
<img width="707" height="186" alt="Screenshot 2026-02-23 104819" src="https://github.com/user-attachments/assets/f3966444-efc5-4944-99a2-3130243be627" />

### INCREMENT
<img width="689" height="212" alt="Screenshot 2026-02-23 104824" src="https://github.com/user-attachments/assets/978e3ec5-7370-46bb-b6a4-ff6ac5f204a1" />




##  Simulation Screenshots:
### ADDITION
<img width="1359" height="481" alt="Screenshot 2026-02-23 104335" src="https://github.com/user-attachments/assets/8d53fcd4-9e6f-4ad8-8f3b-3a0a17d830ed" />

### SUBTRACTION
<img width="1346" height="502" alt="Screenshot 2026-02-23 104351" src="https://github.com/user-attachments/assets/343c18fc-d47a-4c48-a40f-e5e4fda65ad5" />

### MULTIPLICATION
<img width="1358" height="479" alt="Screenshot 2026-02-23 104426" src="https://github.com/user-attachments/assets/f91db1d4-629a-4a83-8852-fcb8fead089b" />


### DIVISION
<img width="1362" height="471" alt="Screenshot 2026-02-23 104440" src="https://github.com/user-attachments/assets/818db3d3-6446-46a5-a8bd-251880cce1bc" />

### OR
<img width="1360" height="507" alt="Screenshot 2026-02-23 104456" src="https://github.com/user-attachments/assets/19ce9400-5cd2-45a6-9781-3c8b0803db73" />

### AND
<img width="1361" height="461" alt="Screenshot 2026-02-23 104510" src="https://github.com/user-attachments/assets/dc1a1ae5-8b92-4314-b9f6-c9ad2c1b6f3b" />

### XOR
<img width="1360" height="428" alt="Screenshot 2026-02-23 104523" src="https://github.com/user-attachments/assets/6be1c173-43bd-4bc8-9311-f2f8362b080d" />

### NEGATIVE(NOT)
<img width="1361" height="448" alt="Screenshot 2026-02-23 104543" src="https://github.com/user-attachments/assets/0bcc38e2-9700-49bc-942b-93ec39f4ee62" />

### DECREMENT
<img width="1366" height="481" alt="Screenshot 2026-02-23 104601" src="https://github.com/user-attachments/assets/4b013c4f-a006-4a92-98a1-96b021cb1e42" />

### INCREMENT
<img width="1369" height="454" alt="Screenshot 2026-02-23 104630" src="https://github.com/user-attachments/assets/82b5bf27-5aac-4ed4-8b9d-3d16c0edd771" />

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
