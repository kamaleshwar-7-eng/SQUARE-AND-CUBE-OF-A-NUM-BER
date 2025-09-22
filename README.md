# SQUARE AND CUBE OF A NUMBER
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
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR  
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
<img width="500" height="312" alt="kamaleshsqr2-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/eab2ccb4-e638-46e6-aec8-b6da3d659d4d" />
<img width="500" height="312" alt="kamaleshsqr1-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/b87fd7df-8c18-44dd-bc02-fc412f607258" />

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
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```


## OUTPUT
<img width="500" height="312" alt="kamaleshcbe1-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/71a67e02-415c-49c3-923b-9663f4cbb5d6" />
<img width="500" height="312" alt="kamaleshcbe1-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/b3c8c1d3-9707-4aea-a850-69b34840075c" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
