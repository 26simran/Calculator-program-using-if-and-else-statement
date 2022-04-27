#include <stdio.h>  
int main()  
{  
    // declare local variables  
    char opt;  
    int n1,n2;   
    float res;  
    printf (" Select an operator (+, -, *, /) to perform an operation in C calculator \n ");  
    scanf ("%c", &opt); // take an operator  
    printf (" Enter the first number: ");  
    scanf(" %d", &n1); // take fist number  
    printf (" Enter the second number: ");  
    scanf (" %d", &n2); // take second number  
      
    if (opt == '+')  
    {  
        res = n1 + n2; /* add two numbers*/  
        printf (" Addition of %d and %d is: %f", n1, n2, res);  
    }  
      
    else if (opt == '-')  
    {  
        res = n1 - n2; /*subtract two numbers*/ 
        printf (" Subtraction of %d and %d is: %f", n1, n2, res);  
    }  
}
