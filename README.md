### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/*1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.*/

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: JAYAGANAPATHI S
RegisterNumber: 24900059
*/
![Screenshot 2024-12-02 122748](https://github.com/user-attachments/assets/0bc92fac-240d-4195-869a-3838755c25a1)

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="337" alt="316518867-a2de142e-af82-4443-8483-1f1ef531ca36" src="https://github.com/user-attachments/assets/67a506ef-da7f-4016-9ce0-db37124dd2ac">

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="607" alt="316518922-07292aa6-3f8b-4fbc-b4ee-6315b3ee4af8" src="https://github.com/user-attachments/assets/d817efce-eb30-4fc6-b1bf-edfeac49c29b">

**RESULTS**
the output of encoder to data flow has been executed successfully.



