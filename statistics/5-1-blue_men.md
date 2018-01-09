[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> Question: Given summary statistics for a normally-distributed population, what percent of American males are between 5' 10" and 6' 1" tall, making them eligible for admission into Blue Man Group?  
>>  
>> How I solved it: Using the scipy.stats.norm() function, I created a frozen random distribution object using the provided mean and standard deviation of the population of American male heights. Then I subtracted the CDF at value 5' 10" from the CDF at value 6' 1", resulting in the percent of the population found between those two end points.  
>>  
>> Solution:  
>> CDF at 5 ft 10 in: 0.489639027865  
>> CDF at 6 ft 1 in: 0.832385865496  
>> CDF between 5 ft 10 in and 6 ft 1 in: 0.342746837631  
>> Therefore approximately 34.3% of all American males fall within the height requirements to join Blue Man Group.
