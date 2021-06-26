#include  <stdio.h>
#code by J4CK H3CK
#https://github.com/J4CKH3CK
//Compiler version gcc  6.3.0

int main()
{
  
  int choose, num1, num2;
  printf("<<<<<<<<Calculator by J4CK H3CK>>>>>>>>\n\n");
      
  do{      
  printf("1 > Addiction\n");
  printf("2 > Subtraction\n");
  printf("3 > Multiplication\n");
  printf("4 > Division\n");
  printf("5 > Exit\n");
  printf("Choose:");
  scanf("%d",&choose); 
  
  switch(choose)
  {
      case 1 : printf("First num >>");
               scanf("%d",&num1);
               printf("Second num >>");
               scanf("%d",&num2);
               printf("%d + %d = %d\n\n", num1, num2, num1 + num2);
             break;
      case 2 : printf("First num >>");
               scanf("%d",&num1);
               printf("Second num >>");
               scanf("%d",&num2);
               printf("%d - %d = %d\n\n", num1, num2, num1 - num2);
             break;
      case 3 : printf("First num >>");
               scanf("%d",&num1);
               printf("Second num >>");
               scanf("%d",&num2);
               printf("%d * %d = %d\n\n", num1, num2, num1 * num2);
             break;
      case 4 : printf("First num >>");
               scanf("%d",&num1);
               printf("Second num >>");
               scanf("%d",&num2);
               printf("%d / %d = %d\n\n", num1, num2, num1 / num2);
             break;
      case 5 : printf("\n<Okay Bye Bye> Have a nice Day <<J4CK H3CK>>");             
             break;
       
      default : printf("Sorry its invalid Input :( \n");
   }
  
  
  }while (choose !=5);
  
  return 0;
}
