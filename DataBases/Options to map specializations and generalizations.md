The generalized class C is split into specialized classes $\{S_1,S_2,...S_m\}$ , where C's attributes are  $\{k,a_1,...a_n\}$  k is the primary key  
The following options are available to us:

1. Multiple relationships for the sub-classes and the super-classes.
	create a relationship L for the super class with attributes   $\{k,a_1,...a_n\}$ and primary key k, and create relationship $S_i$ with attributes $\{k\}U\{attributes of S_i\}$ and primary key k.This option is the most general allowing any  kind of specialization.
2. Multiple relationships only for the sub-classes
	This option requires that the super-class must have total participation in the inheritance.
3. One relationship with an attribute named type
	This solution only works for non-overlapping sub-classes
4. One relationship with logical attribute type
	Can be used for both overlapping and non-overlapping inheritance and 