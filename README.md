# Lab Assignment 09, Due on [Canvas](https://psu.instructure.com/courses/2174978/modules/items/35174873), Mar. 30 at 11:59pm
## What does the distribution of the sample mean look like when the population is heavily skewed?

The main objective of today's lab is to use python tools to understand and illustrate how a sample mean behaves for various sample sizes.

**Objective**:  Using the massive flights dataset from Lab 6, extract the column called AIR_TIME and then investigate the behavior of sample means for samples from this column of various sizes.  

**Your assignment** is as follows:

1. Repeat the steps in Lab 6 that create the giant `Table` object, called `flights`, with 5.8 million rows of data.  We only need the column called `AIR_TIME` so reduce the `flights` object to just that column using this code:
```
flights = flights.select('AIR_TIME')
```

2. Delete the `AIR_TIME` values that equal `nan` (which means "not a number") using this code:




9. _(Optional, for an extra point):_ In Section 14.x, roulette.  How many games of the customer betting on red are necessary in a given day for the casino to make money with probability 99%?  

10.  Finally, make sure that your Jupyter notebook only includes code and text that is relevant to this assignment.  For instance, if you have been completing this assignment by editing the original code from Section 13.2, make sure to delete the material that isn't relevant before turning in your work.

When you've completed this, you should select "Print" from the File menu, then save to pdf using this option.  The pdf file that you create in this way is the file that you should upload to Canvas for grading.  We have found that if you can select the "A3" paper size from the advanced options, this seems to solve the problems that are sometimes encountered in this step.
