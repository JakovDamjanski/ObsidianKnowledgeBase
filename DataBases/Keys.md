Definitions:
- Super key - a super key of the relational schema R $\{A_1,A_2,...,A_n\}$ is a subset of the attributes S of R which functionally determines all of the attributes in R. (THere are no two tuples r in R for which $t_1[S]=t_2[S]$ 
- Key - K is a minimal super key, removing any attribute from K would cause K to no longer be a super key of R
- Super key can also be defined as any set of attributes S which contains the key of R

If a relational schema has multiple keys then each one of them is a _candidate key_.
One of the candidate keys is chosen to be a _primary key_, while the others are _secondary keys_.

A super key can be defined as a group of attributes whose closure contains all of the attributes of the relationship.

A candidate key is a minimal super key, no proper subsets of its attributes satisfy the properties of a super key.