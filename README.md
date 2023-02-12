# Palindrome_Number

#include<stdio.h>
#include<conio.h>
#include<alloc.h>

int main()
{
   int n, n1 , rev=0, rem ;
   printf("Enter the number: ");
   scanf("%d",&n);
   n1=n;
   while(n>0)
   {
      rem=n%10;
      rev=rev*10+rem;
      n=n/10;
   }
   if(n1==rev)
   {
      printf("Given number is palindrome \n");
   }
   else
   {
      printf("Given number is not palindrome \n");
   }
   return 0;
}   
