---
title: 
author:
partner:
date:
---
## (5 pts)
What does the following assembly program, which uses the three-instruction instruction set of this week, compute? MOV R4, 20; MOV R9, 18; ADD R4, R4, R9;
MOV R5, 30; ADD R9, R4, R5; MOV 20, R9.

## (5 pts)
List the basic register/memory transfers and operations that occur during each clock cycle for the following program, based on the three-instruction instruction set of this week: MOV R0, 1; MOV R1, 9; ADD R0, R0, R1;

## (5 pts)
Add a new instruction to the six-instruction instruction set of this week that performs a jump if two registers are equal, to a location specified by a 4-bit offset. Extend the datapath, control unit, and the controller’s FSM as needed (use opcode 0110).

## (5 pts)
Using the six-instruction instruction set of this week, write an assembly program for the following C code, which computes the sum of the first N numbers, where N is another name for D[9]. Hint: use a register to first store N.

```c
i=0;
sum=0;
while ( i!=N ) {
  sum = sum + i;
   i = i + 1;
}
```
