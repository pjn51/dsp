[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

We can see that numpy's generation of random numbers isn't *perfect*, but it's pretty good. By running...

`nums = np.random.random(1000)`

`num_pmf = thinkstats2.Pmf(nums)`

`thinkplot.pmf(num_pmf,linewidth=0.1)`

...we can see the resulting distribution of values. 

![pmf](https://github.com/pjn51/ThinkStats2/blob/master/ch4_ex1.png)

However, when we visualize the CDF by running...

`aa`

...we can see that the function is *pretty good* at generating a even distribution. 

![cdf](https://github.com/pjn51/ThinkStats2/blob/master/ch3_ex2.png)
