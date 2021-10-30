# checking-prime-number
a c program to check the given number is a prime number or not
#include<stdio.h>
int checkforprime(int);
int i;
int main()
{
	int n,primeno;
	printf("\n recursion:check a number is prime number or not:\n");
	printf("input any positive number:");
	scanf("%d",&n);
	i=n/2;
	prime no=check for prime(n);
	if(prime no==1)
	printf("the number %d is a prime number\n\n",n);
	return 0;
	{
	  if(i==1)
	{
		return 1;
		
	}
	else if(n%i==0)
	{
		return 0;
	}
	else
	{i=i-1;
	check for primu(n);
	}
	}

}
