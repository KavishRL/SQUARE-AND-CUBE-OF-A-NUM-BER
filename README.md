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
<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/8235beb2-6fda-4cd9-8ad0-12c1f058a4f2" />
<img width="572" height="158" alt="image" src="https://github.com/user-attachments/assets/5137f092-b1a8-4c71-8324-76b5f3502a86" />


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
<img width="1919" height="845" alt="image" src="https://github.com/user-attachments/assets/6c8bb27f-5ddf-45bf-8033-60bc79eebc42" />
<img width="640" height="176" alt="image" src="https://github.com/user-attachments/assets/ff00dfa7-3b88-43f8-bf96-694adb62e07d" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
