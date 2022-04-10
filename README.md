# Grading-System
To grade marks of kids.
include<stdio.h>
main()
{
	printf(" Enter your marks : "); //Ask user for marks 
	int m; //declaring m as integer 
	scanf("%d",&m); //reads the marks entered
	if ((m<=100) && (m>=85)) // required else if ladder
	{
		printf("\n Congratulations! You got A grade.");
	}
	else if ((m<=84) && (m>=70))
	{
		printf("\n Well done, you got B grade.");
	}
	else if ((m<=69) && (m>=55))
	{
		printf("\n You got C grade. Please try to improve.");
	}
	else if ((m<=54) && (m>=40))
	{
		printf("\n You got D grade. Improvement is required.");
	}
	else if ((m<=39) && (m>=0))
	{
		printf("\n You got F grade. You are failed.");
	}
	else if ((m>100) || (m<0)) // for invalid input 
	{
		printf("\n Invalid marks. Please enter valid marks.");
	}
return 0;
} 
