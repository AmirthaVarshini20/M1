
# EX-01-Datatypes-Operators
## AIM:
Write a program to find sum of two integer numbers

## ALGORITHM:
1.	Start the program and declare three integer variables: x, y, and s.
2.	Take input from the user for two integer numbers (x and y).
3.	Add the two numbers and store the result in s.
4.	Print the sum of x and y using printf.
5.	End the program by returning 0.


	
## PROGRAM:


#include <stdio.h>

int main()

{

    int x,y,s=0;
    
    scanf("%d%d",&x,&y);
    
    s=x+y;
    
    printf("Sum of %d and %d=%d",x,y,s);
    
    return 0;
    
}
## OUTPUT:

![Screenshot 2025-04-29 170734](https://github.com/user-attachments/assets/7317a1f3-93c1-4b61-8947-b755f8febc74)
















## RESULT:
Thus the program to find sum of two integer numbers has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to check whether a number is positive or negative using if-else.

# ALGORITHM:
1.	Declare a variable to store the input value num. 
2.	Use the scanf function to read the value of num from the user.
3.	Check if the value of num is greater than zero.
4.	If num is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's a negative number.
6.      End the program.

# PROGRAM:
#include <stdio.h>

int main()
{
    int num;
    scanf("%d", &num);
    
    if(num >= 0)
    {
        
        printf("Number is positive.");
    }
    else
    {
       
        printf("Number is negative.");
    }

    return 0;
}
# OUTPUT:
![image](https://github.com/user-attachments/assets/b6da0530-6a6c-463a-bec2-4df8a7333fdb)











# RESULT:
Thus the program to read num values and check whether number is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find maximum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Start the program and declare two floating-point numbers x and y.
2.	Ask the user to input two numbers, and store them in x and y.
3.	Compare the two numbers to find which one is greater.
4.	Use a conditional (ternary) operator to choose and print the larger number.
5.	End the program by returning 0. 

## PROGRAM:


#include <stdio.h>
int main()
{
    float x,y;
    scanf("%f%f",&x,&y);
    (x>y)?printf("Maximum between %.2f and %.2f is %.2f",x,y,x):printf("Maximum between %.2f and %.2f is %.2f",x,y,y);
    return 0;
}
## OUTPUT:

![image](https://github.com/user-attachments/assets/8ab2f657-a4dd-4dff-9db3-36d68f763c17)









## RESULT:
Thus the program to find maximum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to find the absolute value of a number entered by the user through the keyboard without using predefined function using simple if statement.

## ALGORITHM:
1.	Start the program and declare two integer variables: x and y.
2.	Take input from the user for an integer value and store it in x.
3.	Check if the number is negative using an if condition.
4.	If it's negative, make it positive by multiplying with -1, then print it; otherwise, just print the number.
5.	End the program by returning 0.



## PROGRAM:


#include <stdio.h>
int main()
{
    int x,y;
    scanf("%d",&x);
    if (x<0)
    {
        y=-x;
        printf("Absolute value = %d",y);
    }
    else
    {
        printf("Absolute value = %d",x);
    }
    return 0;
}
## OUTPUT:
![image](https://github.com/user-attachments/assets/e586d058-a724-44b7-8ec6-358b5774704d)









	

## RESULT:
Thus the program to find the absolute value of a number using simple if statement has been executed successfully.



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables for marks:s1, s2, s3 and total, and also float variables per.
3.	Input the marks for three subjects.
4.	Calculate total marks: total = s1 + s2 + s3
5.	Calculate percentage: per = tot / 3.0
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:


#include <stdio.h>
int main()  
{
    int s1,s2,s3,total;
    float per;
    scanf("%d%d%d",&s1,&s2,&s3);
        total=s1+s2+s3;
        per=(total/3.0);
    printf("Total Marks = %d\n",total);
    printf("Percentage = %.2f\n",per);
    if(s1<40 || s2<40 || s3<40 || per<36){
        printf("Division = Fail\n");
    }else{
   if (per>=60){
        printf("Division = First\n");
    }else if(per >=48){
        printf("Division = Second\n");
    }else if(per>=36){
        printf("Division = Pass\n");
    }}
    return 0;
}

## OUTPUT:
![image](https://github.com/user-attachments/assets/c9fd8c63-0d93-418d-865e-a07129ad7c64)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

