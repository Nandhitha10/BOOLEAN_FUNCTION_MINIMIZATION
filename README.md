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
module booleanfunction(a,b,c,d,w,x,y,z,f1,f2); input a,b,c,d,w,x,y,z; output f1,f2; wire
x1,x2,x3,x4,x5,x6,x7,x8,x9,x10; assign x1= (~a)&(~b)&(~c)&(~d); assign x2= (a)&(~c)&
(~d); assign x3= (~b)&(c)&(~d); assign x4= (~a)&(b)&(c)&(d); assign x5= (b)&(~c)&(d);
assign f1= x1|x2|x3|x4|x5; assign x6= (x)&(~y)&(z); assign x7= (~x)&(~y)&(z); assign x8=
(~w)&(x)&(y); assign x9= (w)&(~x)&(y); assign x10= (w)&(x)&(y); assign f2=
x6|x7|x8|x9|x10; endmodule

Developed by: RegisterNumber:*/
NANDHITHA S 24900454

**RTL realization**

**Output:**

**RTL**
![Screenshot 2024-12-10 120039](https://github.com/user-attachments/assets/4c9a9d88-44c6-4fa9-8086-3ec07dd5b590)

**Timing Diagram**
![Screenshot 2024-12-10 120039](https://github.com/user-attachments/assets/6d4f0fb1-ebb7-40ce-bb9c-ad42aac23c94)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

