Data Visualization practice

Now you can use NumPy to analyze and graph your own datasets! You should practice building your intuition about not only what the data says, but what conclusions can be drawn from your observations.

Instructions

1.  Practice what you’ve just learned with a dataset on sunflower heights! Imagine that you work for a botanical garden and you want to see how the sunflowers you planted last year did to see if you want to plant more of them.

Calculate the mean and standard deviation of this dataset. Save the mean to sunflowers_mean and the standard deviation to sunflowers_std.

2.  We can see from the histogram that our data isn’t normally distributed. Let’s create a normally distributed sample to compare against what we observed.

Generate 5,000 random samples with the same mean and standard deviation as sunflowers. Save these to sunflowers_normal.

3.  Now that you generated sunflowers_normal, uncomment (remove all of the #) the second plt.hist statement. Press run to see your normal distribution and your observed distribution.

4.  Generally, 10% of sunflowers that are planted fail to bloom. We planted 200, and want to know the probability that fewer than 20 will fail to bloom.

First, generate 5,000 binomial random numbers that represent our situation. Save them to experiments.

5.  What percent of experiments had fewer than 20 sunflowers fail to bloom?

Save your answer to the variable prob. This is the approximate probability that fewer than 20 of our sunflowers will fail to bloom.

6.  Print prob. Is it likely that fewer than 20 of our sunflowers will fail to bloom?
