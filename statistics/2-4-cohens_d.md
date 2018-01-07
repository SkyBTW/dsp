[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> Question: Are firstborn babies lighter or heavier than other babies?
>>
>> How I solved it: Using totalwgt_lb, I calculated *mean* weight for all firstborns, *mean* weight for all non-firstborns, and the associated *pooled variance*. Using these three numbers as inputs, I calculated Cohen's *d* to observe the difference in weight, if any, between these two groups. Finally, I calculated Cohen's *d* using the same newborn groups, but with length of pregnancy.
>>
>> Solutions (rounded to 3 decimals):
>>
>>     Mean weights of firstborns: 7.201 lb
>>     Mean weights of all other newborns: 7.326 lb
>>     Pooled variance: 1.980
>>     Cohen's d: -0.089 stand devs
>>
>>     Mean pregnancy length - firstborns: 38.601 weeks
>>     Mean pregnancy length - all other newborns: 38.523 weeks
>>     Pooled variance: 7.302
>>     Cohen's d: 0.029 stand devs
>>
>> When comparing just the calculated means of the two groups of newborns, firstborn babies are slightly lighter than non-firstborns. That said, I interpret the Cohen's *d* value of ~-0.089 as less than a tenth of a standard deviation separating the means of these two groups, indicating an unnoticeable difference in the real world.  
>>  
>> The difference in pregnancy length between these two groups of newborns resulted in an even smaller Cohen's *d* of ~0.029, which I also interpreted as a practically unnoticable difference in duration of pregnancy, indicating that pregnancies of firstborns were less than 0.03 standard deviations longer than those of non-firstborns.
