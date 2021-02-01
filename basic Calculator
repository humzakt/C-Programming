/*
		Humza Khawar 
		Calculator through functions

*/

#define _CRT_SECURE_NO_WARNINGS 
#include <stdio.h>

int sum(int n1, int n2); 	//Declaration 
int minus(int n1, int n2);
int multiply(int n1, int n2);
float divide(int n1, int n2);

int main()
{
	char operator = 'A'; //initialization
	int num1, num2;
	
	
	printf("\n Enter First Number : ");
	scanf_s("%d", &num1);
	printf("\n Enter Second Number : ");
	scanf_s("%d", &num2);
	printf("\nEnter Operator or press q to exit : ");
	while ((operator!='q') && (operator!='Q') && (operator!='+') && (operator!='-') && (operator!='/') && (operator!='*'))//keeps asking for operator
	{
		scanf(" %c", &operator);
	}

	if ((operator!='q') && (operator!='Q'))
	{
		switch (operator)//switch statement for all operator cases

		{
		case '+':
		{
			printf("\n %d + %d = %d\n", num1, num2, sum(num1, num2));
			break;
		}
		case '-':
		{
			printf("\n %d - %d = %d\n", num1, num2, minus(num1, num2));
			break;
		}
		case '*':
		{
			printf("\n %d * %d = %d\n", num1, num2, multiply(num1, num2));
			break;
		}
		case '/':
		{
			if (num2 != 0)
			{
				printf("\n %d / %d = %.2f\n", num1, num2, divide(num1, num2));
			}
			else
				printf("\n Zero division error\n");
			break;
		}

		default:
		{
			printf("\nInvalid Input. Try Again!");
			break;
		
	}

	return 0;
}
int sum(n1, n2)//sum function
{
	return (n1 + n2);
}
int minus(n1, n2)//minus function
{
	return (n1 - n2);
}
int multiply(n1, n2)//multiplication function
{
	return (n1 * n2);
}
float divide(n1, n2)//division function
{
	return ((float)n1 / n2);
	
}
