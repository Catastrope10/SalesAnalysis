# Sales Analysis
Using Python and Pandas

First, I start by assessing our data for:

Quality: issues with content. Low-quality data is also known as dirty data.
Tidiness: issues with structure that prevent easy analysis. Untidy data is also known as messy data.
Then cleaning our data:

* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the datatypes (to_datetime, type)
* Extract data from values
* Merge all datasets into one dataset
  
Once I have cleaned up our data a bit, I move to the data exploration section.

In this section, I explore 5 high-level business questions related to our data:

* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should I display advertisements to maximize the likelihood of customers buying products?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

To ansIr these questions I walk through many different pandas & matplotlib methods. They include:

* Concatenating multiple csvs together to create a new DataFrame (pd. concat)
* Adding columns
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labeling our graphs
