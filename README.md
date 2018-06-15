# Some wxMaxima boolean functions

Operator **->** means implication.<br/>
Operator **<->** means equality.<br/>
Operator **xor** means exclusive or.<br/>

# FUNCTIONS:

  Checks if boolean formula is identically true or false.<br/>
	Params: f is formula, val is true or false.<br/>
	Returns true or false.<br/>
	
*bool_is_identically(f, val);*<br/><br/>


  Checks if two boolean formulas are equivalent.<br/>
	Params: f is the first formula, g is the second formula.<br/>
	Returns true or false.<br/>
	
*bool_equivalent_formulas(f, g);*<br/><br/>


  Makes a truth table (matrix) based on formula.<br/>
	Params: formula is formula.<br/>
	Returns matrix.<br/>

*bool_make_truth_table(formula)*
