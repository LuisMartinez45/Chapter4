# chapter4

## exercises chapter 4 
### Exercise 4.1
```c
#include <stdio.h>

int main(void){
  printf("Luis Felipe Martinez Gonzalez\n");
  printf("School id: 2009087\n");
  printf("Date Birth: 05/05/2002\n");

  return 0;
}
```
### Exercise 4.2
```c
#include <stdio.h>

#include <stdio.h>

int main(void)
{
printf("*****\n*\n*\n***\n*\n*\n*****\n");

return 0;
}
```
### Excercise 4.3
```c
#include <stdio.h>

int width;          
int height;         

int area;           
int perimeter;      

int main() {
	height = 5;
	width = 3;

    perimeter = 2*(height + width);
	printf("Perimeter = %d inches\n", perimeter);
	
	area = height * width;
	printf("Area  = %d square inches\n", area);

return(0);
}
```

### Excercise 4.4
```c
#include <stdio.h>

int main() {
	printf("H   H EEEEE L     L      OOO\n");
	printf("H   H E     L     L     O   O\n");
	printf("H   H E     L     L     O   O\n");
	printf("HHHHH EEEEE L     L     O   O\n");
	printf("H   H E     L     L     O   O\n");
	printf("H   H E     L     L     O   O\n");
	printf("H   H EEEEE LLLLL LLLLL  OOO\n");

	return(0);
}
```
### Excercise 4.5
```c
#include <stdio.h>

float floatnum;     /* a floating-point number */
int intnum;         /* an integer */
char character;     /* a character */

int main() {
	floatnum = 1.0;
	intnum = 1;
	character = 'A';

	printf("%f as %%d: %d\n", floatnum, floatnum);
	printf("%d as %%f: %f\n", intnum, intnum);
	printf("%c as %%d: %d\n", character, character);

	return(0);
}
```
### Exercise 4.6
```c
#include <stdio.h>

int main()
{
   
    int numero=0;
    int divisores=0;
    int primo=0; 
   
    do
    {
        printf("\nNumero.....: ");
        scanf(" %d",&numero);
        if(numero!=-1 && numero>0)
        {
           
            primo=0;
            divisores=2;
            while(divisores<numero  && primo!=1)
            {
                if(numero%divisores==0) primo=1;
                divisores++;
            }

            if (primo==0)
            {
                printf("\nEl numero %d es primo",numero);
            }
            else
            {
                printf("\nEl numero %d no es primo",numero);
            }
        }
    } while(numero!=-1);
    return 0;
}
```
