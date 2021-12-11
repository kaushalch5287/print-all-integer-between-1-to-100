//# print-all-integer-between-1-to-100
#include <stdio.h>

int main()
{
    int i;


    for(i=1; i<=100; i++)
    {
        printf("%d\n", i);
    }

    return 0;
}

//Write a C program to print all natural numbers from 1 to n. – using while loop
Answer:-

#include <stdio.h>
int main()
{
int i, last;
 printf("Print all natural numbers from 1 to ");
 scanf("%d", &last);
 i=1;
 while(i<=last)
 {
 printf("%d\n", i);
 i++;
 }
 return 0;
}

//Write a C program to print all natural numbers in reverse (from n to 1). – using
while loop

#include <stdio.h>
int main()
{
 int n;

 printf("Enter value of n ");
 scanf("%d", &n);
while(n>=1)
 {
 printf("%d\n", n);
 n--;
 }
return 0;
}

//Write a C program to print all alphabets from a to z. – using while Loop
Answer

#include <stdio.h>
int main()
{
 char rh = 'a';
printf("Alphabets from a - z are \n");
 
while(rh<='z')
 {
 printf("%c\n",rh);
 rh++;
 }
 return 0;
}

//Write a C program to print all even numbers between 1 to 100. – using while loop
Answer

#include <stdio.h>
int main()
{
 int i, n;
 printf("Print all even numbers till ");
 scanf("%d", &n);
printf("All even numbers from 1 to %d are \n", n);
 i=1;
 while(i<=n)
 {
 if(i%2==0)
 {
 printf("%d\n", i);
 }
 i++;
 }
 return 0;
}

//Write a C program to print all odd number between 1 to 100

#include<stdio.h>
int main(){
int i;
for(i=1;i<=100;i++)
 {
 if(i%2==1)
 {
 printf("%d\n", i);
 }
 }
 return 0;
}

//Write a C program to find sum of all natural numbers between 1 to n.
Answer

#include <stdio.h>
int main()
{
 int i, n, sum=0;
 printf("Enter upper limit ");
 scanf("%d", &n);
 for(i=1; i<=n; i++)
 {
 sum += i;
 }
 printf("Sum of first %d natural numbers = %d", n, sum);
 return 0;
}

//Write a C program to find sum of all even numbers between 1 to n

#include <stdio.h>
int main()
{
 int i, n, sum=0;
 printf("Enter upper limit ");
 scanf("%d", &n);
 for(i=2; i<=n; i+=2)
{ 
 sum += i;
 }
printf("Sum of all even number between 1 to %d = %d", n, sum);
return 0;
}

//Write a C program to find sum of all odd numbers between 1 to n.
#include <stdio.h>
int main()
{
 int i, n, sum=0;
 printf("Enter upper limit ");
 scanf("%d", &n);
for(i=1; i<=n; i+=2)
 {
 sum += i;
 }
 printf("Sum of odd numbers = %d", sum);
 return 0;
}

//Write a C program to print multiplication table of any number.
Answer

#include <stdio.h>
int main()
{
 int i, num;
 printf("Enter number to print table ");
 scanf("%d", &num);
for(i=1; i<=10; i++)
 {
 printf("%d * %d = %d\n", num, i, (num*i));
 }
 return 0;
}

//Write a C program to count number of digits in a number.
Answer

#include <stdio.h>
int main() {
 long long n;
 int count = 0;
 printf("Enter an integer: ");
 scanf("%lld", &n);

 while (n != 0) {
 n /= 10; 
 ++count;
 }
 printf("Number of digits  %d", count);
 return 0;
}
