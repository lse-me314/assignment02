# Lab 2: The Shape of Data

You should clone this repository to get started with this lab.  The URL to clone is [https://github.com/lse-me314/assignment02](https://github.com/lse-me314/assignment02).  **You can find detailed instructions on how to do this [here](https://lse-me314.github.io/instructions).**

### Resources

* Use the other files in this repository for the exercise.  
* Don't omit reading the the great book _R for Data Science_.  [Chapter 12](http://r4ds.had.co.nz/tidy-data.html) is a fantastic resource for understanding data reshaping.  
* Examine the tutorial on [How to Reshape a Data.frame](how-to-manipulate-dataframe.ipynb).

### Assignment

1.  **Identifying the characteristics of "tidy" data.**

    a.  What makes the following example "non-tidy"?

    ![](nontidy.png)

    b.  Inspect the R object [`cmpdata.RData`] from the file of the same name.  (You can access this by opening the file from the Files pane of Rstudio.)  What makes this data non-tidy?

2.  **Reshaping simple examples in R.**

    a.  From the `cmpdata` object, replicate the reshaped object `cmpdataLong` from the lecture notes, using the **reshape2** package.  (Just use the same syntax as in the lecture notes.)

    b.  Try using **dplyr** on `cmpdataLong` to "spread" this back into the wide format.

3.  **Reshaping more complex examples in R.**

    Update the [assignment-2-complex-example-r.ipynb](assignment-2-complex-example-r.ipynb) to reshape the same dataset we used in (3). But this time we will do it in R.

### Solutions

Solutions to each assignment will be made available on the next day after each lab.
