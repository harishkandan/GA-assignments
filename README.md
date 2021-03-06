# Olympics Dataset - Case Study

Load the olympics dataset (olympics.csv), which was derrived from the [Wikipedia](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table) entry on All Time Olympic Games Medals.

### Question - 1:
Create a dataframe with following data cleanup to make this file redable.
* Create a function load_data to read CSV file and convert CSV data to dataframe.
* Skip first row
* Rename column containing 01, 02 and 03 to Gold, Silver and Bronze
* Split country name and country code and add country name as data frame index
* Remove extra unnecessary characters from country name.
* Drop the column Totals
* Return dataframe.

### Question - 2:
Write a function to get first country details from dataframe we got from load_data function.
* Create a function first_country.
* Return results for first country.


### Question - 3:
Which country has won the most gold medals in summer games?
* Create a function gold_medal to get name of country who won most gold medals.
* Return country name.

### Question - 4:
Which country had the biggest difference between their summer and winter gold medal counts?
* Create a function biggest_difference_in_gold_medal to get name of country who has biggest difference between their summer and winter gold medal counts.
* Return country name.

### Question - 5:
Write a function to update the dataframe to include a new column called "Points" for Games which is a weighted value where each gold medal counts for 3 points, silver medals for 2 points, and bronze
medals for 1 point. The function should return only the column (a Series object) which you created.
* Create a function get_points.
* Return dataframe with points column and index.

### Question - 6 
Write a function to perform k-means clustering.
* Create a fucntion k_means
* return cluster centers

# Complex numbers assignment
Note:

* You are not allowed to use any internal `complex number` library or a python package.

Define a class called `complex_number` which accepts 2 parameters:

* x: int64, float64, represents real component of the complex number
* y: int64, float64, represents imaginary component of the complex number

Example, `complex_number(3, 5)` means 3 is the real part of the complex number and 5 is the imaginary part of the complex number. Such a number is represented as 3 + 5i.

Here is [a resource](http://www.careerbless.com/aptitude/qa/complex_numbers_imp.php) to help you with the required information to solve this assignment. You can take help from other online resources as well.

### Questions:

Define the follwoing operations for the class: 

* representation in the form of x + yi when used with `print` command
* '+'
* '-'
* '*'
* '/'
* abs()

* Note that these operations should be compatible with `int` and `float` datatypes as well

Also, define following methods.


* real() [Returns real component of the complex number]
* imag() [Returns complex component of the complex number]
* argument() [Returns argument of the complex number]
* conjugate() [Returns conjugate of the complex number]

Include error handling
