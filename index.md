## Welcome to _AP Stats in R_! 

This site is my attempt at providing a resource for former, current, and future teachers and students of AP Statistics to learn R. 

Throughout the different tutorials, I will show you how to use R to do the skills taught in the AP Statistics curriculum. Eventually, I may also add some other content. 

### Organization

This site is organized according to the chapters of _The Practice of Statistics, 4th Ed._ by Daren S. Starnes, Dan Yates, and David S. Moore. I don't use any actual content from the book, but I have organized it the same way in the hopes that that helps you understand how everything fits together.

### Style

The tutorial documents will include explanations of how things work, but also blocks of code like the following: 

```r
#first we calculate the average
average = (1+2+3+4+5)/5
#then we print it out
average
```

I'll do my best to break down these code segments so you know exactly what R is doing with different functions and operations.

### About the Author

My name is Peter Moon; I am a former AP Statistics student, a former AP Statistics teacher, and a current PhD student in Mathematics Education at University of Maryland, College Park. If you are curious about the other work I do, feel free to check out my university website [here](https://terpconnect.umd.edu/~pmoon/ 'Peter's university website') 

If you have questions, comments, or concerns about _AP Stats in R_, please feel free to reach out to me at my university email account, pmoon (at) umd (dot) edu.

### Table of Contents/Progress Checklist

Each sub-section of a chapter has a tutorial document and also a downloadable RMarkdown (.rmd) file that you can open in R. If you do not have R installed, please see the tutorial [here](https://techvidvan.com/tutorials/install-r/). Please install BOTH R and RStudio as it will make your life significantly easier!

1. **Chapter 1: Exploring Data**
	1. Analyzing Categorical Data
		1. Conditional Counts & Total Counts ([tutorial](ch1/1.1.a)/[rmd](ch1/1.1.a.rmd))
		2. Frequency Tables ([tutorial](ch1/1.1.b)/[rmd](ch1/1.1.b.rmd))
		3. Pie Charts & Bar Charts ([tutorial](ch1/1.1.c)/[rmd](ch1/1.1.c.rmd))
		4. Segmented Bar Charts **<-- I am here**
	2. Graphical Displays of Quantitative Data
	3. Numerical Summaries of Quantitative Data
2. **Chapter 2: Modeling Distributions of Data**
	1. Describing Location in a Distribution
	2. Normal Distributions
3. **Chapter 3: Describing Relationships**
	1. Scatterplots & Correlation
	2. Least-Squares Regression
8. **Chapter 8: Confidence Intervals**
	1. Estimating a Population Proportion
	2. Estimating a Population Mean
9. **Chapter 9: Significance Testing**
	1. Testing a Population Proportion
	2. Testing a Population Mean
10. **Chapter 10: Comparing Two Populations or Groups**
	1. Comparing Two Proportions
	2. Comparing Two Means
11. **Chapter 11: Chi-Square and Inference for Categorical Distributions**
	1. Chi-Square Goodness-of-Fit Tests
	2. Inference for Relationships
12. **Chapter 12: More Regression Skills**
	1. Inference for Linear Regression
	2. Transforming to Achieve Linearity