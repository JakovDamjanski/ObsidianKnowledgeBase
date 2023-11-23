Functional dependencies are constraints which are derived from the semantics of the relationships between the data in the real world.

Definition: A set of attributes X functionally determines another set of attributes Y, if the value of X determines a single value for Y. (if X -> Y is a function).

If X and Y are functionally dependent, more specifically if X -> Y (Y depends on X ),then any number of entries with the corresponding X values should have the same (between them) Y values.

i.e. if $t_1[x]$  then $t_2[Y]$ 

If the data in the real world has certain functional dependencies and entries in the data-base are in violation of these constraints, then that data is inconsistent.

IMPORTANT NOTE: 
We cannot determine whether a functional dependency exists based upon the current state of the database, we can only see if it doesn't, or if we know the relationships between the data in the real world, we can see if a certain functional dependency is violated (the constraint of it is violated).

From a given set of functional dependencies we can derive new dependencies, using [[Armstrong's rules]]

