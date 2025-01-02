# BOOLEAN_FUNCTION_MINIMIZATION
**DATE:4/10/2024**

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**TRUTH TABLE**

**F1**

![image](https://github.com/user-attachments/assets/e21184fd-1ff8-479d-b34c-e462f6428dc3)

**F2**

![image](https://github.com/user-attachments/assets/4caef441-d61d-4046-b0fb-a5cc41fa63a8)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**BOOLEAN MINIMIZATION**

**F1**
![image](https://github.com/user-attachments/assets/c5a96fa2-05de-4950-aea3-ce5dc005bb4a)

**F2**
![image](https://github.com/user-attachments/assets/b04d0be8-d8e2-470d-b8d3-0b06700da7ee)


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: THAVANESH B

Register Number: 212224040352

```

i)F1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));0
endmodule

```


**RTL realization**

**F1**
![image](https://github.com/user-attachments/assets/17d35396-91f5-4a33-ab41-881448b234bf)

**F2**
![image](https://github.com/user-attachments/assets/d8531afb-475c-41e1-845d-53a7b4d9af8c)


**TIMING WAVEFORM**

**F1**
![image](https://github.com/user-attachments/assets/239dafd6-8990-4ea9-b441-513a3e5229f3)

**F2**

![image](https://github.com/user-attachments/assets/26dba6b4-26df-42e1-abe4-bb25649c2ee9)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

