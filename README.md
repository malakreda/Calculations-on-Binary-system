-Problem description:
This problem is represented in creating a program to make calculations on binary numbers. 
The used algorithms: (Pseudo code) 
1.	The Addition:  
The bits which are analogous in both numbers are adding to each other and the overflow must be taken in consideration as if the overflow results in 1, then adding 1 to the next bit. 
2.	The subtraction:  
The bits which are analogous in both numbers are subtracted from each other and the overflow must be taken in consideration as if the overflow results in 0, then we take 1 from the next bit. And if the overflow results in 1, then we take 1 from the next bit and converted to 0.  
3.	The first complement:  
The decimal number is converted into binary number, then flip all the bits.  
4.	The second complement:  
The decimal number is converted into binary number, then add 1 to the first complement of that number.  
5.	Inputs and outputs 
 Inputs:  
•	First number  
•	Second number  
•	Calculation type         
          Outputs:  
•	Result of the calculation  
6.	Tests for program evaluation 
 Addition:  
•	Inputs: 1010 and 1001 
•	Output: 1011 
 Subtraction: 
•	Inputs: 1101 and 1010 
•	Output: 0011  
 First complement:  
•	Input: 1010 
•	Output: 0101 
  Second complement:  
•	Input: 1010  
•	Output: 0110  
