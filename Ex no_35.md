# EX 35  C PROGRAM TO CREATE A FILE AND WRITE THE FILE 
## DATE:
## AIM:
To write a program to read a file name from user and create that file and insert student roll 
numbers in to that file.
## Algorithm
To write a program to read a file name from user and create that file and insert student roll 
numbers in to that file.

## Program:
```
#include <stdio.h> 
int main() 
{ 
FILE *p; 
char name[100]; 
int num; 
int id; 
char text[100]; 
float m; 
scanf("%s",name); 
scanf("%d",&num); 
p=fopen("name","w"); 
printf("%s Opened\n",name); 
{ 
scanf("%d %s %f",&id,text,&m); 
fprintf(p,"%d %s %f",id,text,m); 
} 
fclose(p); 
printf("Data added Successfully")
```

## Output:
sample.txt:\
3\
111\
222\
333


## Result:
Thus the program was executed and the output was verified successfully.
