# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
    int i, n;
    srand(time(NULL));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Pseudorandom numbers:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand() % 100);
    }
    return 0;
}
```
# OUTPUT:
<img width="727" height="320" alt="image" src="https://github.com/user-attachments/assets/abb93c05-929b-4e68-90ef-a670dbf5cd6b" />

# RESULT:
The C program for Pseudo Random number generation is executed successfully and the output is verified
