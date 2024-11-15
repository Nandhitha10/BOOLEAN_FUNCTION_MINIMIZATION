# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/ S NANDHITHA 24900454


**RTL realization**
module halfadder(a, b, s, ca);
 input a;
 input b;
 output s;
 output ca;
assign s=a^b;
assign ca=a&b;
endmodule


**Output:**
![Screenshot 2024-11-15 140736](https://github.com/user-attachments/assets/5fd487e4-53bc-4601-a1c0-8902674b0e4b)
![Screenshot 2024-11-15 141510](https://github.com/user-attachments/assets/70d458df-84a2-469a-89aa-cb957bd6e985)


**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

