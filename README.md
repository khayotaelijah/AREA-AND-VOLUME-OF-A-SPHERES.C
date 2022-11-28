/*Calculation of area and volume of a sphere*/
#include <stdio.h>

int main()
{
   int radius;//radius is an integer
   float area, volume, pi;//area, volume, pi are real  numbers
   pi=3.142;//initialize 3.142 to pi
   printf("\n enter radius\t");
   scanf("%d", &radius);//input the radius of the sphere

   area=4*pi*radius*radius;//formula for area of a sphere
   volume=4/3*pi*radius*radius*radius;//formula for volume of a sphere

   printf("\n area=%f", area);
   printf("\n volume=%f", volume);
    return 0;
}
