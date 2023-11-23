For a relationship to be in BCNF the following must be true:
For every nontrivial functional dependency X->A, which is true for the relationship R, it's true that X is a super-key in R.

To get a relationship into BCNF we can perform the following algorithm: 
1. We find all of the keys, based on the algorithm for finding a closure for a set of attributes. 
2. We find every functional dependency which is in violation of BCNF. 
3. We perform a decomposition of the relationship to get relationship schemas which satisfy BCNF
	1.  we first find the set of attributes X for which the following is true $X^+\neq X\land X^+\neq[allAttributes]$ if there are no such sets then the relationship is in BCNF. 
	2. Make a decomposition of R into $R_1(X^+)$ and $R_2(X\cup Rest)$ rest is the set of attributes not in the closure of X.
	3. We return $R_1$ and $R_2$ and repeat steps 1 through 4 for each until there are no more functional dependencies which do not satisfy the condition for BCNF.


Decomposition into BCNF guarantees the a Lossless join, valid data after joining the derived relationships. Decomposition however does not guarantee that all of the initial functional dependencies will remain true after the decomposition, since it divides the attributes between multiple new relationships. 

#3NF is seen as an alternative to BCNF where er preserve the initial functional dependencies.