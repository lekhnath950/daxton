*Program:1* **Program to print a content using printf and puts**





```
// C program to show the use of puts

#include <stdio.h>

int main()
{

    puts("GNDEC");

    puts("LUDHIANA");
 

    getchar();

    return 0;
}
```

```
Output: 
GNDEC
LUDHIANA
```


```
// C program to show the use of printf

#include <stdio.h>
int main()
{

    

    printf("GNDEC LUDHIANA");

    getchar();

    return 0;

}
```

```
Output:
GNDEC LUDHIANA
```

*Program 2* **Program to use different data types
              (int,float,char)**
              
```
#include <stdio.h>

int main()
{

    int a = 1;

    char b = 'G';

    double c = 3.14;

    printf("Hello World!\n");
 

    // printing the variables defined 

    // above along with their sizes

    printf("Hello! I am a character. My value is %c and "

           "my size is %lu byte.\n",

           b, sizeof(char));

    // can use sizeof(b) above as well
 

    printf("Hello! I am an integer. My value is %d and "

           "my size is %lu  bytes.\n",

           a, sizeof(int));
          
          // can use sizeof(a) above as well
 

    printf("Hello! I am a double floating point variable."

           " My value is %lf and my size is %lu bytes.\n",

           c, sizeof(double));

    // can use sizeof(c) above as well
 

    printf("Bye! See you soon. :)\n");

    return 0;
}
```

```
Output: 
Hello World!
Hello! I am a character. My value is G and my size is 1 byte.
Hello! I am an integer. My value is 1 and my size is 4  bytes.
Hello! I am a double floating point variable. My value is 3.140000 and my size i
s 8 bytes.
Bye! See you soon. :)
```





*Program 3* **Program to use arithmetic operators.**

```
/* Program to Perform Arithmetic Operations in C */

#include<stdio.h>

int main()
{
 int a = 12, b = 3;
 int addition, subtraction, multiplication, division, modulus;
 
 addition = a + b; //addition of 3 and 12
 subtraction = a - b; //subtract 3 from 12
 multiplication = a * b; //Multiplying both
 division = a / b; //dividing 12 by 3 (number of times)
 modulus = a % b; //calculation the remainder
 
 printf("Addition of two numbers a, b is : %d\n", addition);
 printf("Subtraction of two numbers a, b is : %d\n", subtraction);
 printf("Multiplication of two numbers a, b is : %d\n", multiplication);
 printf("Division of two numbers a, b is : %d\n", division);
 printf("Modulus of two numbers a, b is : %d\n", modulus);

}
```
```
Output:
Additions of two numbers a,b is : 15
Subtraction of two numbers a,b is : 9
Multiplication of two numbers a,b is: 36
Division of two numbers a, b is : 4
Modulus of two numbers a, b is : 0
```



*Program 4*  **Program to use logical operators.**
```
#include <stdio.h>
main() {

   int a = 5;
   int b = 20;
   int c ;

   if ( a && b ) {
      printf("Line 1 - Condition is true\n" );
   }
	
   if ( a || b ) {
      printf("Line 2 - Condition is true\n" );
   }
   
   /* lets change the value of  a and b */
   a = 0;
   b = 10;
	
   if ( a && b ) {
      printf("Line 3 - Condition is true\n" );
   } else {
      printf("Line 3 - Condition is not true\n" );
   }
	
   if ( !(a && b) ) {
      printf("Line 4 - Condition is true\n" );
   }
	
}
```
```
Output:
Line 1 - Condition is true
Line 2 - Condition is true
Line 3 - Condition is not true
Line 4 - Condition is true
```






*Program 5* **Program to use relational operators.**
```
#include <stdio.h>
main() {

   int a = 21;
   int b = 10;
   int c ;

   if( a == b ) {
      printf("Line 1 - a is equal to b\n" );
   } else {
      printf("Line 1 - a is not equal to b\n" );
   }
	
   if ( a < b ) {
      printf("Line 2 - a is less than b\n" );
   } else {
      printf("Line 2 - a is not less than b\n" );
   }
	
   if ( a > b ) {
      printf("Line 3 - a is greater than b\n" );
   } else {
      printf("Line 3 - a is not greater than b\n" );
   }
   
   /* Lets change value of a and b */
   a = 5;
   b = 20;
	
   if ( a <= b ) {
      printf("Line 4 - a is either less than or equal to  b\n" );
   }
	
   if ( b >= a ) {
      printf("Line 5 - b is either greater than  or equal to b\n" );
   }
}
```
Output:
```
Line 1 - a is not equal to b
Line 2 - a is not less than b
Line 3 - a is greater than b
Line 4 - a is either less than or equal to  b
Line 5 - b is either greater than  or equal to b
```



*Program 6*  **Program to use increment and decrement operators.**

// Increment operator in c
```
#include <stdio.h>
int main()
{
     int i=1;
     while(i<10)
     {
         printf("%d ",i);
         i++;
     }    
}
```

Output:
```
1 2 3 4 5 6 7 8 9
```

// Decrement operator in C
```
#include <stdio.h>
int main()
{
    int i=20;
    while(i>10)
    {
         printf("%d ",i);
         i--;
    }    
}
```


Output:

```
20 19 18 17 16 15 14 13 12 11
```


*Program 7*  **Program to use conditional statements: if-else, if else ladder**


```
#include <stdio.h> 
int main() 
{ 
	int i = 20; 

	// Check if i is 10 
	if (i == 10) 
		printf("i is 10"); 

	// Since i is not 10 
	// Check if i is 15 
	else if (i == 15) 
		printf("i is 15"); 

	// Since i is not 15 
	// Check if i is 20 
	else if (i == 20) 
		printf("i is 20"); 

	// If none of the above conditions is true 
	// Then execute the else statement 
	else
		printf("i is not present"); 

	return 0; 
} 
```

Output:
```
i is 20
```



// C program to illustrate nested-if statement 
```
#include <stdio.h> 

int main() 
{ 
	int i = 25; 

	// Check if i is between 0 and 10 
	if (i >= 0 && i <= 10) 
		printf("i is between 0 and 10"); 

	// Since i is not between 0 and 10 
	// Check if i is between 11 and 15 
	else if (i >= 11 && i <= 15) 
		printf("i is between 11 and 15"); 

	// Since i is not between 11 and 15 
	// Check if i is between 16 and 20 
	else if (i >= 16 && i <= 20) 
		printf("i is between 16 and 20"); 

	// Since i is not between 0 and 20 
	// It means i is greater than 20 
	else
		printf("i is greater than 20"); 
} 
```
Output:
```
i is greater than 20
```


