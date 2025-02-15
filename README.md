# Excel_Sheet_Mathematics_Solution
Excel Sheet Mathmetics Solution : How to understand write a code 
Problem: Find the remainder when one number is divided by another		
Step 1 - Understand the Problem		
Is there any term in the problem that you don't understand? Read and understand it		
See if you can explain this clearly to a 10 year old		
Step 2 - Design Test Data/Test Cases (Input and Expected Output)			6
Assumptions, Constraints  & Questions			
1	Number should be a whole number		
2	It can range from 1 to 99999		
3	No special characters, spaces, decimal numbers, alphabets are accepted		
4	We will ignore -ve numbers even though it is possible to get remainder with them		
Test Cases or Test Data		
Category	Input	Exptected Output
Valid	11,2	1
	6,3	0
	18,5	3
	4,1	0
		
		
		
		
		
Invalid	abc, 2	"Invalid"
	6, 1@23	"Invalid"
	1,1.2	"Invalid"
	1,2/3	"Invalid"
	-1,0	"Invalid"

  Step 3: Solution
Get the first number - dividend
Get the second number - divisor
If 1st or 2nd number is out of range , print "Invalid". End
If 1st or 2nd number is a special character, blank, alphanumeric, then print "Inavlid". End
Divide dividend by divisor and store the resulting remainder. We can use the modulo operator to achieve this.
Print the value of remainder on the screen. End
