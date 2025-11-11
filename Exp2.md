## EXP NO:2 C PROGRAM FOR PASSING STRUCTURES AS FUNCTION ARGUMENTS AND RETURNING A STRUCTURE FROM A FUNCTION
## Aim:
To write a C program for passing structure as function and returning a structure from a function

## Algorithm:
1.	Define structure numbers with members a and b.
2.	Declare variable n of type numbers.
3.	Prompt the user to enter values for a and b.
4.	Input values for a and b into n using scanf.
5.	Call the add function with n as an argument.
6.	Print the result returned by the add function.
7.	Return 0
 
## Program:

```c
#include <stdio.h>
struct numbers {
    int a, b, sum;
};
struct numbers add(struct numbers n) {
    n.sum = n.a + n.b;
    return n;
}
int main() {
    struct numbers n, result;
    printf("Enter two numbers: ");
    scanf("%d %d", &n.a, &n.b);
    result = add(n);
    printf("Sum = %d\n", result.sum);
    return 0;
}

```

## Output:

<img width="823" height="308" alt="image" src="https://github.com/user-attachments/assets/8a8868a9-bdb5-466d-9117-82ee91f87f2e" />

## Result:
Thus, the program is verified successfully
