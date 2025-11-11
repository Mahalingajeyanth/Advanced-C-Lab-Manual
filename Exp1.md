## EXP NO:1 C PROGRAM FOR ARRAY OF STRUCTURE TO CHECK ELIGIBILITY FOR THE VACCINE.

## Aim:
To write a C program for array of structure to check eligibility for the vaccine person age above 6 years of age.

## Algorithm:
1.	Declare structure eligible with age (integer) and n (character array)
2.	Declare variable e of type eligible
3.	Input age and name using scanf, store in e
4.	If e.age <= 6
-	Print "Vaccine Eligibility: No"
Else
-	Print "Vaccine Eligibility: Yes"
5.	Print details (e.age, e.n)
6.	Return 0
 
## Program:
```c
#include <stdio.h>

struct eligible {
    char name[50];
    int age;
};

int main() {
    struct eligible e;

    printf("Enter name: ");
    scanf("%s", e.name);
    printf("Enter age: ");
    scanf("%d", &e.age);

    if(e.age > 6)
        printf("Vaccine Eligibility: Yes\n");
    else
        printf("Vaccine Eligibility: No\n");

    printf("Name: %s\nAge: %d\n", e.name, e.age);

    return 0;
}

```

## Output:

<img width="822" height="289" alt="image" src="https://github.com/user-attachments/assets/81469666-443c-488f-b0b3-2a7a705e084b" />


## Result:

Thus, the program is verified successfully.
