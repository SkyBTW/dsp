[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> The problem/question: If we surveyed children asd asked how many children in their household, the data would carry a bias that over-represents households with lots of children, and those with no children would be under-represented. Using a data set representing the *actual* distribution of children per household, calculate a predicted distribution of children per household from surveying children, then polt the Actual and Predicted to compare. Finally, Calculate the means of these two distributions.  
>>  
>> How I solved it: Using the provided 'numkdhh' data and the thinkstats2 package, I converted the provided data into a pmf distribution of probabilities, representing the distribution of actual children per household. Next I copied that pmf and multiplied each probability by the cooresponding value of children per household, and re-normalized, to generate the expected, biased survey results, and graphed both of these generated distributions on the same axes for comparison. Finally, I used the provided *Mean* class to calculate the mean of the each data set.  
>>  
>> Solutions (rounded where necessary):  
>> Comparison of Actual distribution vs Predicted, Biased distribution:  
>> ![](https://github.com/SkyBTW/ThinkStats2/blob/master/Prework_-_Stats_figs/Q2.png)  
>> Mean of actual data: 1.024 children/household  
>> Mean of predicted survey data: 2.404 children/household
