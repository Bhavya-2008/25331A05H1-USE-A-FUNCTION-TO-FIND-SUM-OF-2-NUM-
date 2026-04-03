# 25331A05H1-USE-A-FUNCTION-TO-FIND-SUM-OF-2-NUM-
#include <stdio.h>
// Function declaration
int sum(int a, int b);
int main() 
{
    int num1, num2, result;
    // Input two numbers
    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);
    // Function call
    result = sum(num1, num2);
    // Output the result
    printf("Sum = %d", result);
    return 0;
}
// Function definition
int sum(int a, int b) 
{
    return a + b;
}
