# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**<img width="443" height="667" alt="image" src="https://github.com/user-attachments/assets/7aab17bd-3234-416b-9362-ffe71052b7ce" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:YOKESH.V RegisterNumber:*/25018968


**RTL realization**<img width="538" height="357" alt="image" src="https://github.com/user-attachments/assets/0abbda58-78eb-4d27-a2a4-bf704b9bb1ff" />


**Output:**<img width="538" height="357" alt="Screenshot 2025-10-28 134208" src="https://github.com/user-attachments/assets/915e62cc-e827-4c81-b6cd-ee2c0f9f6ec4" />


**RTL**<img width="558" height="313" alt="image" src="https://github.com/user-attachments/assets/a816be73-d702-4291-b5e2-bc3b8fc41b95" />


**Timing Diagram**<img width="558" height="313" alt="image" src="https://github.com/user-attachments/assets/4e62217c-9004-46e1-bb5f-92d4e36a2edd" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

