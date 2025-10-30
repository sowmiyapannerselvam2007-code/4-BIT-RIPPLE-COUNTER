# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**<img width="851" height="853" alt="Screenshot 2025-10-30 220603" src="https://github.com/user-attachments/assets/38d559f3-3178-4517-b06f-a524e3575d31" />



/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:P.SOWMIYA RegisterNumber:25018423
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**<img width="932" height="412" alt="Screenshot 2025-10-30 220612" src="https://github.com/user-attachments/assets/081e63f1-4ae5-4d11-ae52-4a6af625aff9" />



**TIMING DIGRAMS FOR 4 Bit Ripple Counter**<img width="1155" height="406" alt="Screenshot 2025-10-30 220620" src="https://github.com/user-attachments/assets/8ca92d55-29be-4708-8999-e5d4968d9de8" />


**RESULTS** HENCE IT IS VERIFIRD
