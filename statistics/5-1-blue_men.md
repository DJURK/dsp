[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> 

To model this distribution, we do the following:

mu = 178<br />
sigma = 7.7<br />
height = scipy.stats.norm(loc=mu, scale=sigma)

These are the respective heights in CM (5'10" and 6'1")

low = dist.cdf(177.8) <br />
high = dist.cdf(185.4)  
high-low = 0.34209468294595308

~34.2% of the U.S. male population is in the range.
