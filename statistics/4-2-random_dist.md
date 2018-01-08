[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> Question: To verify whether the function random.random generates numbers with a truly uniform distribution, generate 1000 random numbers between 0 and 1, then interpret the PMF and CDF.  
>>  
>> How I solved it: I imported the package 'random' and ran random.random 1000 times, each time appending the result to the end of an initially empty list. Using the provided thinkstats2 package, I converted this array to each a PMF and CDF structure, then plotted using the appropriate classes from thinkplot.  
>>  
>> Solution:  
>>  
>> ![PMF plot](https://github.com/SkyBTW/ThinkStats2/blob/master/Prework_-_Stats_figs/Q3-rand_pmf.png)
>>  
>> ![CDF plot](https://github.com/SkyBTW/ThinkStats2/blob/master/Prework_-_Stats_figs/Q3-rand_cdf.png)
>>  
>> The PMF plot shows that each value in the data set has a probability of about 0.0010 of being generated, being approximately uniform accorss all values.  
>> The CDF plot displays an approximately stright line.  
>> Both of the above plots show a uniform distribution of generated numbers between 0 and 1.
