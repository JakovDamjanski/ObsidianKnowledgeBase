Normalisation is the process of removing redundancies and improving the design and subsequent translation into relationships of the ER model. It involves decomposition of inefficient mega relationships by dividing their attributes into smaller relationships. An inefficient relationship is one which is in violation of the normal forms.
Normalisation seeks to give answers to the following issues:
- Anomalies during updating of data entries: - When a update in a single data entry creates inconsistent data
- Anomalies in data insertion: - Problems and inconsistency caused by new data being inserted into the data base.
-  Anomalies in data erasure: - Removal of data that makes our remaining data inconsistent.

Normalisation involves decomposition of inefficient mega relationships by dividing their attributes into smaller relationships. An inefficient relationship is one which is in violation of the normal forms.
The normal forms are the following:
- 1NF - all attributes are atomic
- 2NF (deprecated) - every non primary attribute is fully functionally dependent on the primary key
- (BCNF) [[Boyce Codd Normal Form]] - the relationships don't contain redundant information which is susceptible to anomalies.
- [[3NF]],4NF,5NF

For each relationship the following are true:
- each relationship which is in 2NF  is also in 1NF 
- each relationship which is in 3NF  is also in 2NF 
- each relationship which is in BCNF  is also in 3NF 



This process covers two related topics:
[[Functional dependencies]]
[[Keys]]
