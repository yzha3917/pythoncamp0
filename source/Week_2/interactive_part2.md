##Interactive Python Part 1


###Arithmetic Expressions
int() takes the "whole" part of a decimal number.  
float() takes a number with an accuracy of 12/15 decimal points.  

For division,   
int(a) / int(b) = int(a/b)  
float(a) / float(b) = float(a/b)

Priority:  
Simply by order of appearance.


###Variables

	a += 1
	same as a = a + 1


###Functions

	def Function_name(Variable_1,Variable_2):
		Result = Variable_1 * Variable_2
		return Result
		
###More Operations

##### Operators

	31 // 10 
	returns 3, 
	
	31 % 10
	returns 1, 
	
	1 % 10
	returns 1.
	
#####Module:  
A set of functions, previously developed by others.   
Calling module by typing  
 
	import Module_Name  
	
	
###Logic and comparisons

	If a == 10 :
		print "True"
	elif a == 5 :
		print "False"
	else:
		print "Nah"
		
"==" means Comparison
		
###Programming tips 1
* Case sensitivity  
* String vs. Number
* = vs. ==

###Local vs. Global variables
* Anything created inside a function, is a local variable. 
* By using "global variable", the variable in function becomes global one. 


###SimpleGUI
* Program Structure
	* Globals (state)
	* Helper functions
	* Classes
	* Define event handlers
	* Create a frame
	* Register event handlers
	* Start frame & timers
	
###Programming tips 2
* "return" is important in a function. 
* Otherwise, this function returns "None"




		