# Basic-C.-Programs-
learning to words C program
LEARING TO WORDS C PROGRAM……….

	VERIABLE AND CONSTANT PROGRAM..
#include <stdio.h>
#include <conio.h>
void main()
{
    clrscr();
    int age;
    const int x = 100;

    printf("enter your age \n");
    scanf("%d", &age);

    printf("your age is: %d\n", age);
    printf("x value is: %d", x);
    getch();
}

	ONE single program for ALL operations….
#include <stdio.h>
#include <conio.h>
void main()
{
    clrscr();
    int a, b;

    printf("Enter first number: ");
    scanf("%d", &a);
    printf("Enter second number: ");
    scanf("%d", &b);

    printf("\n--- ARITHMETIC ---\n");
    printf("Addition = %d\n", a + b);
    printf("Subtraction = %d\n", a - b);
    printf("Multiplication = %d\n", a * b);
    printf("Division = %d\n", a / b);
    printf("Modulus = %d\n", a % b);

    printf("\n--- RELATIONAL ---\n");
    printf("a > b = %d\n", a > b);
    printf("a < b = %d\n", a < b);
    printf("a == b = %d\n", a == b);
    printf("a != b = %d\n", a != b);
    printf("a >= b = %d\n", a >= b);
    printf("a <= b = %d\n", a <= b);

    printf("\n--- LOGICAL ---\n");
    printf("(a>0 && b>0) = %d\n", (a > 0 && b > 0));
    printf("(a>0 || b>0) = %d\n", (a > 0 || b > 0));
    printf("!(a==b) = %d\n", !(a == b));

    printf("\n--- BITWISE ---\n");
    printf("a & b = %d\n", a & b);
    printf("a | b = %d\n", a | b);
    printf("a ^ b = %d\n", a ^ b);
    printf("~a = %d\n", ~a);
    printf("a << 1 = %d\n", a << 1);
    printf("a >> 1 = %d\n", a >> 1);

    getch();
}

	PROGRMAM TO BUILT IF, ELSE AND ELSEIF…. 
#include <stdio.h>
#include <conio.h>
void main()
{
    clrscr();
float  tempareture;
print(“enter temperature:”);
scanf(“%f”,&temperature);
if (temperature>20){
     printf(“wear the sweater \n”);
}
                      else if (temperature>20 && temperature<30){
                              printf(“normal \n”);
                        }
                      else if (temperature is 100){
                       printf(“it is to hot on the Ac\n”);
                     }
else{
printf(“wear the T shirt and drink water \n”)
}
}

