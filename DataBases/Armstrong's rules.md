Armstrong's rules are a combination of logic and set theory which allow us to derive new functional dependencies from existing ones.

The three rules are: 
1. Reflexivity: 
	If Y is a subset of X, then X->Y.
	This boils down to a group of attributed determining a subset of itself.
2. Union/Decomposition (Augmentation):
	For any group of attributes if $\{A_1,...,A_m\}\rightarrow B_i$   for each $i=1,...,n$ then  $\{A_1,...,A_m\}\rightarrow \{B_1,...,B_n\}$ . The inverse is also true, if $\{A_1,...,A_m\}\rightarrow \{B_1,...,B_n\}$ then $\{A_1,...,A_m\}\rightarrow B_i$   for each $i=1,...,n$ .
3. Transitivity:
	If the functional dependencies are true $\{A_1,...,A_m\}\rightarrow \{B_1,...,B_n\}$
	$\{B_1,...,B_n\}\rightarrow \{C_1,...,C_k\}$, then its true that $\{A_1,...,A_m\}\rightarrow \{C_1,...,C_k\}$


[[Closure]]
