# R-Programming
Coursera R- Programming
The R language is a dialect of which of the following programming languages?
Your Answer		Score	Explanation
Lisp			
C			
S	Correct	1.00	R is a dialect of the S language which was developed at Bell Labs.
Fortran			
Total		1.00 / 1.00	
Question 2
The definition of free software consists of four freedoms (freedoms 0 through 3). Which of the following is NOT one of the freedoms that are part of the definition?
Your Answer		Score	Explanation
The freedom to improve the program, and release your improvements to the public, so that the whole community benefits.			
The freedom to run the program, for any purpose.			
The freedom to sell the software for any price.	Correct	1.00	
This is not part of the free software definition. The free software definition does not mention anything about selling software (although it does not disallow it).
The freedom to redistribute copies so you can help your neighbor.			
Total		1.00 / 1.00	
Question 3
In R the following are all atomic data types EXCEPT
Your Answer		Score	Explanation
character			
array	Correct	1.00	'array' is not an atomic data type in R.
numeric			
complex			
Total		1.00 / 1.00	
Question 4
If I execute the expression x <- 4 in R, what is the class of the object `x' as determined by the `class()' function?
Your Answer		Score	Explanation
list			
numeric	Correct	1.00	
integer			
matrix			
Total		1.00 / 1.00	
Question 5
What is the class of the object defined by x <- c(4, TRUE)?
Your Answer		Score	Explanation
integer			
numeric	Correct	1.00	The numeric class is the "lowest common denominator" here and so all elements will be coerced into that class.
character			
list			
Total		1.00 / 1.00	
Question Explanation

R does automatic coercion of vectors so that all elements of the vector are the same data class.
Question 6
If I have two vectors x <- c(1,3, 5) and y <- c(3, 2, 10), what is produced by the expression cbind(x, y)?
Your Answer		Score	Explanation
a vector of length 2			
a 3 by 3 matrix			
a 2 by 2 matrix			
a 3 by 2 numeric matrix	Correct	1.00	The 'cbind' function treats vectors as if they were columns of a matrix. It then takes those vectors and binds them together column-wise to create a matrix.
Total		1.00 / 1.00	
Question 7
A key property of vectors in R is that
Your Answer		Score	Explanation
the length of a vector must be less than 32,768			
elements of a vector can be of different classes			
elements of a vector all must be of the same class	Correct	1.00	
elements of a vector can only be character or numeric			
Total		1.00 / 1.00	
Question 8
Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[1]] give me?
Your Answer		Score	Explanation
a numeric vector of length 1.	Correct	1.00	
a list containing the letter "a".			
a list containing the number 2.			
a list containing a numeric vector of length 1.			
Total		1.00 / 1.00	
Question 9
Suppose I have a vector x <- 1:4 and y <- 2:3. What is produced by the expression x + y?
Your Answer		Score	Explanation
an integer vector with the values 3, 5, 5, 7.	Correct	1.00	
a numeric vector with the values 1, 2, 5, 7.			
a warning			
a numeric vector with the values 3, 5, 3, 4.			
Total		1.00 / 1.00	
Question 10
Suppose I have a vector x <- c(17, 14, 4, 5, 13, 12, 10) and I want to set all elements of this vector that are greater than 10 to be equal to 4. What R code achieves this?
Your Answer		Score	Explanation
x[x > 10] <- 4	Correct	1.00	You can create a logical vector with the expression x > 10 and then use the [ operator to subset the original vector x.
x[x > 4] <- 10			
x[x == 10] <- 4			
x[x > 10] == 4			
Total		1.00 / 1.00	
Question 11
In the dataset provided for this Quiz, what are the column names of the dataset?
Your Answer		Score	Explanation
1, 2, 3, 4, 5, 6			
Ozone, Solar.R, Wind			
Month, Day, Temp, Wind			
Ozone, Solar.R, Wind, Temp, Month, Day	Correct	1.00	You can get the column names of a data frame with the `names()' function.
Total		1.00 / 1.00	
Question 12
Extract the first 2 rows of the data frame and print them to the console. What does the output look like?
Your Answer		Score	Explanation

  Ozone Solar.R Wind Temp Month Day
1     9      24 10.9   71     9  14
2    18     131  8.0   76     9  29

  Ozone Solar.R Wind Temp Month Day
1    41     190  7.4   67     5   1
2    36     118  8.0   72     5   2
Correct	1.00	You can extract the first two rows using the [ operator and an integer sequence to index the rows.

  Ozone Solar.R Wind Temp Month Day
1    18     224 13.8   67     9  17
2    NA     258  9.7   81     7  22

  Ozone Solar.R Wind Temp Month Day
1     7      NA  6.9   74     5  11
2    35     274 10.3   82     7  17
Total		1.00 / 1.00	
Question 13
How many observations (i.e. rows) are in this data frame?
Your Answer		Score	Explanation
45			
153	Correct	1.00	You can use the `nrow()' function to compute the number of rows in a data frame.
129			
160			
Total		1.00 / 1.00	
Question 14
Extract the last 2 rows of the data frame and print them to the console. What does the output look like?
Your Answer		Score	Explanation

    Ozone Solar.R Wind Temp Month Day
152    34     307 12.0   66     5  17
153    13      27 10.3   76     9  18

    Ozone Solar.R Wind Temp Month Day
152    31     244 10.9   78     8  19
153    29     127  9.7   82     6   7

    Ozone Solar.R Wind Temp Month Day
152    18     131  8.0   76     9  29
153    20     223 11.5   68     9  30
Correct	1.00	The `tail()' function is an easy way to extract the last few elements of an R object.

    Ozone Solar.R Wind Temp Month Day
152    11      44  9.7   62     5  20
153   108     223  8.0   85     7  25
Total		1.00 / 1.00	
Question 15
What is the value of Ozone in the 47th row?
Your Answer		Score	Explanation
34			
63			
21	Correct	1.00	The single bracket [ operator can be used to extract individual rows of a data frame.
18			
Total		1.00 / 1.00	
Question 16
How many missing values are in the Ozone column of this data frame?
Your Answer		Score	Explanation
78			
43			
9			
37	Correct	1.00	
Total		1.00 / 1.00	
Question Explanation

The `is.na' function can be used to test for missing values.
Question 17
What is the mean of the Ozone column in this dataset? Exclude missing values (coded as NA) from this calculation.
Your Answer		Score	Explanation
53.2			
42.1	Correct	1.00	
31.5			
18.0			
Total		1.00 / 1.00	
Question Explanation

The `mean' function can be used to calculate the mean.
Question 18
Extract the subset of rows of the data frame where Ozone values are above 31 and Temp values are above 90. What is the mean of Solar.R in this subset?
Your Answer		Score	Explanation
334.0			
212.8	Correct	1.00	
185.9			
205.0			
Total		1.00 / 1.00	
Question Explanation

You need to construct a logical vector in R to match the question's requirements. Then use that logical vector to subset the data frame.
Question 19
What is the mean of "Temp" when "Month" is equal to 6?
Your Answer		Score	Explanation
79.1	Correct	1.00	
75.3			
90.2			
85.6			
Total		1.00 / 1.00	
Question 20
What was the maximum ozone value in the month of May (i.e. Month = 5)?
Your Answer		Score	Explanation
18			
115	Correct	1.00	
100			
97			
Total		1.00 / 1.00
