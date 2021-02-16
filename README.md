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

