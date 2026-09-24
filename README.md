# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END


```

## CALCULATION
<img width="255" height="214" alt="image" src="https://github.com/user-attachments/assets/ceb7846f-c0cc-4478-b976-1c7baad64b81" />


## OUTPUT
<img width="1600" height="844" alt="image" src="https://github.com/user-attachments/assets/09bd557c-e0b2-4b92-92c1-040b14815817" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END


```

### CALCULATION 
<img width="256" height="223" alt="image" src="https://github.com/user-attachments/assets/18e2aa1f-9da7-443a-a6ec-7a3e82c0dbd1" />


## OUTPUT
<img width="1600" height="852" alt="image" src="https://github.com/user-attachments/assets/62aa0e8b-8b19-4f1d-aa1d-fd3f63ae9e3f" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


