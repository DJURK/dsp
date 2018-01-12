[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> 

t = np.random.random(1000)

pmf = thinkstats2.Pmf(t)<br />
thinkplot.Pmf(pmf, linewidth=0.1)<br />
thinkplot.Config(xlabel='Random variate', ylabel='PMF')

cdf = thinkstats2.Cdf(t)<br />
thinkplot.Cdf(cdf)<br />
thinkplot.Config(xlabel='Random variate', ylabel='CDF')

The CDF plot of the 1000 random numbers is pretty much a straight line from 0 to 1 on both axes.  This means that every value has the same chance of being selected from the random sample.
