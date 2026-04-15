# Lab-Report-3[Reverse the digits of a given number]

## STudent Information
Name:Tasmim Jannat
ID:26002159
Course:BSC in CSE

## Experiment Title
 Reverse the digits of a given number

## Objectives  
1.	To learn how to use loops in C. 
2.	To reverse the digits of a given number. 
3.	To understand arithmetic operations and control flow. 

## Algorithm 
Step 1: Start
Step 2: Input the number
Step 3: Set reverse = 0
Step 4: While number is not equal to 0
•	Get last digit = number % 10
•	Reverse = reverse * 10 + last digit
•	 number = number / 10
Step 5: Display reverse
Step 6: End

## Code
#include<stdio.h>
int main(){
    int number,reverse=0,remainder;

    printf("Enter Number: ");
    scanf("%d", &number);

    while (number != 0) {
    remainder = number % 10;
    reverse = reverse * 10 + remainder;
    number = number / 10;
    }

    printf("Reversed Number: %d", reverse);
  return 0;
}

## Result  
Input: Enter Number: 1234
Output: Reversed Number: 4321
Input: Enter Number: 56789
Output: Reversed Number: 98765

## Conclusion
  The program successfully demonstrates how to reverse the digits of a number using loops and arithmetic operations in C. This lab helped improve understanding of iteration, number manipulation, and logical problem solving.
