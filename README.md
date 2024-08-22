# EXPERIMENT--01-ALP-FOR-8086

## Name : THARUN SRIDHAR 
## Reg NO : 212223230230
## Date of experiment : 22-08-2024





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [6379h],al;
ret
```

## Output  
 ![image](https://github.com/user-attachments/assets/e19ee665-c30f-4756-8649-e657903a1826)

## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV al,20h;
MOV bl,[8778h];
SUB bl,al;
MOV [8798h],bl;
ret
```
 
## Output  
![Screenshot (1)](https://github.com/user-attachments/assets/65abf027-1c75-4b5d-887d-eacb8ace28ad)

## Multiplication alp 
```
org 100h
MOV al,13h;
MOV bl,2h;
MUL bl;
MOV [6063h],bl;
ret
```

 ## Output  
![Screenshot (2)](https://github.com/user-attachments/assets/4cf88d41-c3d4-430d-9705-1de74a881efa)


## Division alp 
```
org 100h
MOV al,26h;
MOV bl,[2369h];
DIV bl;
MOV [2399h],al;
ret
```

## Output  
![Screenshot (3)](https://github.com/user-attachments/assets/00317f7a-23c4-4e9c-ac2d-276f87606525)

## PROGRAMS FOR LOGICAL OPERATION 
## OR Operation
```
org 100h
mov al, 15h
mov bl, 22h
or al, bl
mov [5454h], al
ret
```

## Output
![Screenshot (4)](https://github.com/user-attachments/assets/d61c2c10-56a3-4018-b289-41c4d9301f61)

## AND Operation 
```
org 100h
mov al, 07h
mov bl, 05h
and al, bl
mov [5000h], al
ret
```

## Output

![Screenshot (5)](https://github.com/user-attachments/assets/b6fcdffd-49f1-414b-b2f3-583012afd6fd)

## XOR Operation
```
org 100h
mov ax, 0A32h
mov bx, 05B7h
xor ax, bx
mov [5050h], ax
ret
```

## Output

![Screenshot (6)](https://github.com/user-attachments/assets/02c96e6a-246d-4d6a-ac33-ba843a226434)

## NOT Operation 
```
org 100h
mov ax, 0F5Bh
not ax
mov [6666h], ax
ret
```

## Output

![Screenshot (7)](https://github.com/user-attachments/assets/dafe65be-699c-4caa-af6f-45ba04528ff8)


## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully. 








