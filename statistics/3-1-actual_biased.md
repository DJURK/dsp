[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> 
These are the actual(pmf) and biased probability mass functions for number of children.

  pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh') <br />
  biased = BiasPmf(pmf, label='biased') <br />

The plot function would be this:

  thinkplot.PrePlot(2) <br />
  thinkplot.Pmfs([pmf, biased]) <br />
  thinkplot.Config(xlabel='Number of children', ylabel='PMF')

and the means are : pmf = 1.0242051550438309, biased = 2.4036791006642821
