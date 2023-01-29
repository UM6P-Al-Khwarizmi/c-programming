### Exercise 1:
- Write a C program that reads two real numbers, and then displays their product, with a precision of three decimal places. 

### Exercise 2:
- Write a C program that allows you to swap the content of two integer variables by passing through a third auxiliary variable. 
- Display the two variables before and after permutation.

### Exercise 3:

- Suppose C program containing the following statements:

```C
int   i =  8;
int   j =  5;
float x =  0.005f;
float y = -0.01f;
char  c = 'c';
char  d = 'd';
```

- Determine the value of these expressions:

    - (3*i - 2*j)%(2*d - c)
    -  2*((i/5) + (4*(j-3))%(i + j - 2))
    -  i <= j
    -  j != 6
    -  c == 99
    -  5*(i + j) > 'c'
    - (i > 0) && (j < 5)
    - (i > 0) || (j < 5)
    - (x > y) && (i > 0) || (j < 5)
    - (x > y) && (i > 0) && (j < 5)

### Exercise 4:

- Analyse the expressions in the program below:

```C
#include <stdio.h>
main()
{
  int a;
  int b;
  int c;

  a = 16;
  b = 2;
  c = 10;

  c += a > 0 && a <= 15 ? ++a : a/b;
  /*
   * What about the following expression? :
   * ----------------------------------
   */
  a > 30 ? b = 11 : c = 100;
}
```
