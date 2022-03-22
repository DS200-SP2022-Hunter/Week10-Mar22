# Lab Assignment 09, Due on [Canvas](https://psu.instructure.com/courses/2174978/modules/items/35174873), Mar. 30 at 11:59pm
## What does the distribution of the sample mean look like when the population is skewed?

The main objective of today's lab is to use python tools to understand and illustrate how a sample mean behaves for various sample sizes.

**Objective**:  Using the massive flights dataset from Lab 6, extract the column called AIR_TIME and then investigate the behavior of sample means for samples from this column of various sizes.  

**Your assignment** is as follows:

1. Repeat the steps in Lab 6 that create the giant `Table` object, called `flights`, with 5.8 million rows of data.  We only need the column called `AIR_TIME` so reduce the `flights` object to just that column using this code:
```
flights = flights.select('AIR_TIME')
```

2. Delete the `AIR_TIME` values that equal `nan` (which means "not a number") using this code:

to be continued

3. Use the `num_rows` method to find the number of observations in the AirTime dataset, then create a histogram of the data.  Your histogram should show that the dataset is skewed toward larger times.

4. Use the `simulate_sample_mean` function from [Section 15.5](https://inferentialthinking.com/chapters/14/5/Variability_of_the_Sample_Mean.html) to generate a histogram of sample means from 10,000 samples of size n=1 from `AIR_TIME`.  What is the shape of the histogram?  Is this what you expected, and why?

5. Now repeat step 4, including answering the questions, using n=5 and n=100.

6. In this case, we are sampling from a population that is entirely known to us.  Therefore, we can calculate the exact value of the population standard deviation.  Find this SD, then calculate the SD of sample means from parts 4 and 5 using the information in Section 14.5.2.

to be continued

9. _(Optional, for an extra point):_ In Section 14.x, roulette.  How many games of the customer betting on red are necessary in a given day for the casino to make money with probability 99%?  

10.  Finally, make sure that your Jupyter notebook only includes code and text that is relevant to this assignment.  For instance, if you have been completing this assignment by editing the original code from Section 13.2, make sure to delete the material that isn't relevant before turning in your work.

When you've completed this, you should select "Print" from the File menu, then save to pdf using this option.  The pdf file that you create in this way is the file that you should upload to Canvas for grading.  We have found that if you can select the "A3" paper size from the advanced options, this seems to solve the problems that are sometimes encountered in this step.
