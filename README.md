
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include <stdio.h>
 int main()
 {
 char ch,ch1,ch2;
 scanf("%c%c%c",&ch,&ch1,&ch2);
 printf("The reverse of %c%c%c is %c%c%c",ch,ch1,ch2,ch2,ch1,ch);
 return 0;
 }

```
## OUTPUT:

![M-1](https://github.com/user-attachments/assets/f62fac00-7860-4626-8910-20205ca22cc7)


## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.






# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>
 int main()
 {
    int a;
    scanf("%d",&a);
    if (a>=0)
    {
        printf("Number is positive.");
    }
    else
    {
        printf("Number is negative.");
    }
return 0;
 }

```
## OUTPUT:

![M-2](https://github.com/user-attachments/assets/b7083c3c-1a8d-4fb2-ac87-245ea38478b5)


## RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 




# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>
 int main()
 {
    int a,b;
    scanf("%d%d",&a,&b);
    if (a<b)
    {
        printf("Minimum between %d and %d is %d",a,b,a);
    }
    else
    {
        printf("Minimum between %d and %d is %d",a,b,b);
    }
    return 0;
 }

```

## OUTPUT:

![M-3](https://github.com/user-attachments/assets/d83b10ac-bc7b-498a-8979-b8d25b436162)


## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.







# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>
 int main(){
 int a;
 scanf("%d",&a);
 if(a==1)
 printf("TRUE");
 }

```
## OUTPUT:

![M-4](https://github.com/user-attachments/assets/59275332-e9c5-4029-bf0c-31af991b82e0)


## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully






# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include <stdio.h>
 int main() {
    int m1, m2, m3, total;
    float percentage;
    printf("Enter marks of three subjects:\n");
    scanf("%d %d %d", &m1, &m2, &m3);
   
    total = m1 + m2 + m3;
    percentage = total / 3.0;
    
    printf("Total Marks = %d\n", total);
    printf("Percentage = %.2f%%\n", percentage);
   
    if (m1 < 33 || m2 < 33 || m3 < 33) {
        printf("Result: Fail (One or more subjects below 33)\n");
    } else if (percentage >= 60) {
        printf("Result: First Division\n");
    } else if (percentage >= 50) {
        printf("Result: Second Division\n");
    } else if (percentage >= 40) {
        printf("Result: Pass\n");
    } else {
        printf("Result: Fail\n");
    }
    return 0;
 }

```


## OUTPUT:
![M-5](https://github.com/user-attachments/assets/3dda00a4-364d-4080-b825-0527eadf1b6e)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

