# Assessment_Solution

Solution

 Aim:- Maximum Optimization with minimum Cost.<br>
	Optimal Point = Optimal value of fixed load<br>

Basic Idea:-  One thing is quite clear that when we are purchasing extra load on-demand then we have to pay ‘2X’ price for the extra load. So, we eventually end up paying an extra 2X price for the extra load.
So, we need to find an optimal value of fixed load in order to cut down our expenses.

Approach:-(Deprovision the Load)<br>
1/ To find an optimal value for our fixed load we need to observe and analyze the previous computation data of our organization.<br>

2/ After analyzing the previous computation data , we will try to find a pattern of our usage.<br>

3/ Let us try to understand what we can observe from our computation data:-<br>
	a/ We have to take a time window (let us say 30 days).<br>
	b/ Our computation data will contain timestamp and computation capacity that is being used at that particular timestamp.<br>
	c/ We have to mainly focus on the extra usage.So, we will calculate how much extra load we are purchasing on-demand for our organization per day. <br>
	d/ Calculate the percentage of extra load we are using every day.<br>
		Let us understand it with small example:-<br>
		i) The percentage for extra load for 5 days are:-<br>
			30%, 40%, 28%, 25%, 35%<br>
		ii) Now, we will calculate the average percentage for these extra
                        Percentages i.e 31.6%.<br>
	 	iii) So, we will increase our fixed load by 31.6%. That is going to be our optimal value for the fixed load.<br>
