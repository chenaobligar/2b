# 2b
#include <stdio.h>
 int main()
 { int age;
   char name [50];
 
 printf("\n Type the Name of the candidate: "); gets(name);
 
 printf("\n Enter The Age : ");
 scanf("%d",&age);
 if(age > 17) 
{ 
printf("\n %s is Eligible for Vote",name);
}
 else 
{ 
printf("\n %s is Not Eligible for Vote",name); 
}
 return 0; 
