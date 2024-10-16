```
Developed by: H Vishinu
Reg NO : 212223220124
```
# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

## F1
```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1= ( (~b & ~d) | (~a & b & d) | (a & b & ~c));
endmodule
```
## F2
```
module exp1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = ( (~y & z)| (x & y) | (w & y) );
endmodule
```
## Truthtable
![image](https://github.com/user-attachments/assets/a7c36e58-46ff-46b3-80a3-30d9e03229ac)
![image](https://github.com/user-attachments/assets/1c288d50-9d1e-4e2c-b924-0b8224281b09)


## RTL 

![Screenshot 2024-09-13 094716](https://github.com/user-attachments/assets/650fad80-a2c2-4c69-ac58-7eee7826e271)
![Screenshot 2024-09-20 082303](https://github.com/user-attachments/assets/004fdab8-b39e-4119-bf02-b7fc9c586353)

## Output:
![Screenshot 2024-09-13 095122](https://github.com/user-attachments/assets/314b1a55-5374-417e-947d-a4457e39f5f0)
![Screenshot 2024-09-20 082718](https://github.com/user-attachments/assets/583fb700-ce78-4822-86c0-db1a7233e0b1)


## Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

