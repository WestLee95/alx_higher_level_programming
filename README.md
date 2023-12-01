/*********THIS HANDLES IMPORT & MODULES IN PYTHON********/


Add.py -> 	A program was developed to import the function add from the file add_0.py.
	Two variables, a and b, were assigned the values 1 and 2, respectively. 
	The program utilized the print function with string formatting
	to display the result of the addition (1 + 2 = 3).
Calc.py ->	A program was crafted to import functions from the file calculator_1.py.
	Two variables, a and b, were defined with values 10 and 5, respectively.
	The program adhered to a limitation of using the print function
	(with string format) no more than four times.
	The functions imported from calculator_1.py were subsequently invoked using these variables.
	The term calculator_1 was employed only once in the file, and the code was 
	designed to avoid execution when imported.
Args.py ->	A programwas developed to display information about its arguments.
	The output includes the number of arguments and the list of arguments.
	If no arguments were passed, it ends with a period and a new line.
	Otherwise, each argument is listed with its position (starting at 1) and value on a new line.
	The code ensures it is not executed when imported.
Infinite_add.py ->	A program has been created to compute the sum of all provided arguments,
		taking into account the possibility of handling large numbers.
		The output displays the result of the addition, followed by a new line.
		The program utilizes the int() function to cast arguments as integers,
		ensuring it is not executed when imported.
Hidden_discovery.py ->		A program was developed to print all names defined by the
			compiled module hidden_4.pyc. 
			The names were displayed in alphabetical order, with one name per line.
			Only names that did not begin with double underscores were printed.
			The code was structured to ensure it would not execute upon import.
Variable_load.py ->	A program was crafted to import the variable a from the file variable_load_5.py,
			and subsequently print its value.
			Importing was achieved without using the asterisk (*) or the __import__ function.
			The code was designed to avoid execution when imported.
