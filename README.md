#include<stdio.h>
#define pi 3.1416
Void main()
{
Int choice ;
Float area, r, s ,l, b;
Printf(“1.circle\n 2.square\n 3. Rectangle\n”);
Printf(“enter your choice”);
Scanf(“%c” ,&choice);
Switch(choice)
{
Case ’1’ : printf(“enter radius:”);
Scanf(“%f”,&r);
Area=pi *r*r;
Printf(“area of circle= %2f\n”, area);
 break;
Case ’2’ : printf(“enter side:”);
Scanf(“%f”, &s);
Area= side*4;
Printf(“area of square= %2f\n”, area);
 break;
Case ’3’ : printf(“enter length and breadth”);
Scanf(“%f %f”,&l,&b);
Area=l*b;
Printf(“area of rectangle= %2f\n”, area);
 break;
default : printf(“invalid!\n”); 
}
}
