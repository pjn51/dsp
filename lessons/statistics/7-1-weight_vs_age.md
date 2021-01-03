[Think Stats Chapter 7 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2008.html#toc70) (weight vs. age)

In order to plot birth weight against the mother's age, I ran...

`thinkplot.scatter(m_age,wgt)
thinkplot.Config(xlabel = "Mother's age",
                ylabel = 'Birth weight (lbs)')`

... which resulted in this scatter plot. 

![scatterplot](https://github.com/pjn51/ThinkStats2/blob/master/ch7_ex.png)

Pearson's correlation is 0.0688 and Spearman's is 0946.  

In order to plot this information using the percentile ranks for birth weight, we have to do a bit more work. First, we have to divide the dataset into groups by birth weight. 

Now, we have to compute the CDFs of mother's age within each group. 
