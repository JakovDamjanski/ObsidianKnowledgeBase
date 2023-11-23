For number of predictors J and number of classes K. If we pick the j-th predictor and split a region containing N number of data points along the threshold $t_j\in R$ ,we can measure the quality of the split using the following metric:
	$Error(i|j,t_j)=1-max(p(k|R))$ , in this case $p(k|R)$ is the proportion of data points labelled as class k.
	To pick the predictor that we use to split a region, we calculate the error for all predictors and pick the one with the lowest error. The total error of the predictor is equal to the weighted average of the Errors for its regions.
	![[Pasted image 20231123020414.png]]
	$N_1,N_2$ are the numbers of data points within each of the regions, while $N$ is their sum(total number of data points)
