# EX 43 C program to Write a function to display queue elements using array.
## AIM:
To Write a function to display queue elements using array.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to display queue elements using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
  

## Program:
```c
float queue[50];
int rear=-1,front=-1,i; 
void display()
{
if(front==-1||front>rear) 
printf("No elements to display\n"); 
else
{
for(i=front;i<=rear;i++) 
printf("%.1f\n",queue[i]);
}
}
void display()
{
if(front==-1||front>rear)
{
printf("No elements to display\n");
else
{
for(i=front;i<=rear;i++)
}

```

## Output:

![image](https://github.com/user-attachments/assets/0ca9b575-a594-4421-8f94-756d72e1a276)


## Result:
Thus the program was executed and the output was verified successfully.
