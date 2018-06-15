# Some wxMaxima boolean functions

Operator "->" means implication.
Operator "<->" means equality.
Operator "xor" means exclusive or.

FUNCTIONS:

  Checks if boolean formula is identically true or false.
	Params: f is formula, val is true or false
	Returns true or false.
	
bool_is_identically(f, val);


  Checks if two boolean formulas are equivalent.
	Params: f is the first formula, g is the second formula.
	Returns true or false.
	
bool_equivalent_formulas(f, g);


  Makes a truth table (matrix) based on formula.
	Params: formula is formula.
	Returns matrix. 

bool_make_truth_table(formula)
