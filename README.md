/*
Name:Victor Maina
REegistration no.:PA106/G/28732/25
Description;Program to display volume and surface are of a cylinder
surface area=(2*PI*radius*radius)+(2*PI *radius*height)
volume=PI*radius*radius*height 
*/
#include<stdio.h>;

int main(){

//declaration for variables
float radius,height;
double volume,surfacearea;
float PI=3.1415926;

//promp the user to enter radius
printf("Enter the radius:");
scanf("%f",&radius);

//prompt the user to enter height
printf("enter the height:");
scanf("%f",&height);

//surface area
surfacearea=(2*PI*radius*radius)+(2*PI*radius*height);

//display surface area
printf("\n surfacearea is%.2f",surfacearea);

//volume
volume=PI*radius*radius*height;

//display volume
printf("\n volume is %.2f",volume);

return 0;
}
