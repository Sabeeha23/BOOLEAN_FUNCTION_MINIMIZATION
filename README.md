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

Developed by: Sabeeha Shaik 
RegisterNumber: 212223230176 */

// Verilog model: Circuits with Boolean expressions
module exp2(E, F, A, B, C, D);
output E,F;
input A, B, C, D;
assign E = A || (B && C) || ((!B) && D);
assign F = ((!B) && C) || (B && (!C) && (!D));
endmodule


**RTL realization**
![Screenshot 2024-03-17 125257](https://github.com/Sabeeha23/BOOLEAN_FUNCTION_MINIMIZATION/assets/150231876/48c9b3bb-c067-42cb-b78f-ead9b8539924)



**Output:**
![2024-03-17 (2)](https://github.com/Sabeeha23/BOOLEAN_FUNCTION_MINIMIZATION/assets/150231876/120fc810-4f00-4d94-9c79-2e14e2ab2483)





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

