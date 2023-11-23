Similar to the [[Classification error]] , it's used to calculate the quality of a given split (by a certain predictor). The Gini index is calculated with the following formula:
	$Gini(i|j,t_j)=1-max(p(k|R)^2)$ 
	To calculate the benefit of picking a certain predictor we use the weighted average of the Gini index of it's regions.