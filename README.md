#include<stdio.h>
int main()
{
    float l,b,area;
    printf("enter the value of length of the rectangle: ");
    scanf("%f",&l);
    printf("enter the value of breadth of the rectangle: ");
    scanf("%f",&b);
    area=l*b;
    printf("area of the given rectanglr is: %.3f",area);
    return 0;

}
