# EXPERIMENT--01-ALP-FOR-8086

# Name : Harish M
# Roll no: 212224110021
# Date of experiment : 31/07/2026





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

## Addition  of 16 bit ALP 


```
org 100h

mov ax, [1100h]
mov bx, [1102h]
add ax, bx
mov [1200h], ax

hlt
```


## Output  

<img width="1917" height="1135" alt="image" src="https://github.com/user-attachments/assets/d225198c-bbb1-4358-a52a-ac89fb4e6ce8" />

 
## Subtraction   of 16 bit numbers  ALP 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
sub ax, bx
mov [1200h], ax

hlt
```
 
## Output  
<img width="1917" height="1131" alt="image" src="https://github.com/user-attachments/assets/92487a9d-1101-4313-b306-cb417416ae87" />




## Multiplication alp 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
mul bx

mov [1200h], ax
mov [1202h], dx

hlt
```
 ## Output  

<img width="1917" height="1096" alt="image" src="https://github.com/user-attachments/assets/cd038ba9-42ba-4e4e-a23f-669ffd81e01b" />




## Division alp 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
mov dx, 0000h
div bx

mov [1200h], ax
mov [1202h], dx

hlt
```



## Output  

<img width="1917" height="1136" alt="image" src="https://github.com/user-attachments/assets/4ad65640-5c1f-4823-a980-451eb3e4fbd7" />


# AND 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
and ax, bx
mov [1200h], ax

hlt
```

# OUTPUT

<img width="1917" height="1133" alt="image" src="https://github.com/user-attachments/assets/fe8ce356-a6a5-4539-8175-cb68966e03b2" />



# NAND 
```
org 100h

mov ax, [1100h]
mov bx, [1102h]
and ax, bx
not ax
mov [1200h], ax

hlt
```
# OUTPOT

<img width="1916" height="1133" alt="image" src="https://github.com/user-attachments/assets/da47fe36-189a-4712-9704-1e9de59265fa" />


# OR 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
or ax, bx
mov [1200h], ax

hlt
```

# OUTPUT

<img width="1917" height="1135" alt="image" src="https://github.com/user-attachments/assets/f38e84dd-19bc-4e1c-a3bd-ee69c75cb9f4" />


# NOR 
```
org 100h

mov ax, [1100h]
mov bx, [1102h]
or ax, bx
not ax
mov [1200h], ax

hlt
```
# OUTPUT

<img width="1917" height="1132" alt="image" src="https://github.com/user-attachments/assets/36221dfa-03d3-4559-8268-a8d8a8041724" />


# XOR

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
xor ax, bx
mov [1200h], ax

hlt
```

# OUTPUT

<img width="1917" height="1135" alt="image" src="https://github.com/user-attachments/assets/c1e5b658-79d4-4861-9c84-21dcb6ee1933" />


# XNOR 

```
org 100h

mov ax, [1100h]
mov bx, [1102h]
xor ax, bx
not ax
mov [1200h], ax

hlt
```
# OUTPUT
<img width="1917" height="1131" alt="image" src="https://github.com/user-attachments/assets/64ca21d8-6385-4153-88d7-f06fd633e91c" />



## Result :
 

Thus, the programs were executed successfully.






