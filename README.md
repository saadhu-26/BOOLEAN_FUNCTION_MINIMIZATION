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

Developed by: RegisterNumber:*/25018432
MINIMIZATION OF BOOLEAN FUNCTION
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
**RTL realization**
<img width="540" height="795" alt="image" src="https://github.com/user-attachments/assets/45e6b3a7-defb-4dfc-83be-8a1d3f75c565" />
<img width="578" height="662" alt="image" src="https://github.com/user-attachments/assets/1bc3e5a3-19ba-42b3-9244-48ddba7e53d0" />
<img width="577" height="596" alt="image" src="https://github.com/user-attachments/assets/ee7c1a6b-3206-440f-bf55-64b3dfcbe3f4" />
<img width="569" height="288" alt="image" src="https://github.com/user-attachments/assets/12b438c7-04c1-42d9-9963-405653dd7eaf" />
**Output:**
<img width="618" height="637" alt="image" src="https://github.com/user-attachments/assets/22064c6e-f77a-4544-aa02-a39581d5b85a" />
**RTL**
**Timing Diagram**
<img width="986" height="394" alt="image" src="https://github.com/user-attachments/assets/817f741e-b12b-4a3a-8c02-41bdeb91b393" />
<img width="967" height="388" alt="image" src="https://github.com/user-attachments/assets/8019032b-f8c0-476c-81de-2c28eea7b121" />
**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
