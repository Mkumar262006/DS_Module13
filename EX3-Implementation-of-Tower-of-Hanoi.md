
# EX3 Implementation of Tower of Hanoi
## DATE:
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
<br>1. Start the program.
<br>2. Check if n is greater than 0.
<br>3.Recursively move n-1 disks from source (x) to auxiliary (z) using destination (y).
<br>4.Print the move of the n-th disk from source (x) to destination (y).
<br>5.Recursively move n-1 disks from auxiliary (z) to destination (y) using source (x).
<br>6.The function is called initially with TOH(n, 'A', 'B', 'C') where 'A', 'B', and 'C' are the rods.
<br>7.End
 
## Program:
```py
/*
Program to implement Tower of Hanoi
Developed by:  MANOJ KUMAR S
RegisterNumber: 212223240082

#include<stdio.h> 
void TOH(int n,char x,char y,char z) 
{ 
if(n>0) 
{ 
TOH(n-1,x,z,y); 
printf("%c to %c",x,y); 
printf("\n"); 
TOH(n-1,z,y,x); 
} 
} 
int main() 
{ 
int n=2; 
TOH(n,'A','B','C'); 
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/fa455837-895f-4d39-b8a4-1bde186b585a)


## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
