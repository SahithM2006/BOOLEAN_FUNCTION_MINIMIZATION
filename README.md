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
![ex2](https://github.com/user-attachments/assets/1399b1d4-9c63-48f7-9f6e-f4d28935bcd8)
![ex3 (2)(6) jpg](https://github.com/user-attachments/assets/2b14ba64-8ff6-437b-a4f9-a433c1cc7a3d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: SAHITH M
RegisterNumber:24000251
```
module experiment2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module experiment2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```


**RTL realization**
![ex 2 resub](https://github.com/user-attachments/assets/55b22b7d-d665-410f-83ed-c872ed280bf3)
![ex 2 resub(1)](https://github.com/user-attachments/assets/f1d5e78a-1758-45b3-938c-bcf388a6e3cc)

**Output:**
***TRUTH TABLE***
![EXP2](https://github.com/user-attachments/assets/be4b5f5e-2f0f-4867-98c5-a9e3a625e385)

***K-MAP***
![K-map_4x4_empty-Photoroom](https://github.com/user-attachments/assets/4b68d8b2-e7ce-43b0-95c9-1e272a764410)
![K-map_4x4_empty](https://github.com/user-attachments/assets/e1707c31-0e69-4732-bd98-199e6ad11e0f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

