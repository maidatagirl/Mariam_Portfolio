# Mariam_Portfolio
Data Science Project Portfolio

# [Project 1: Sales Analysis](https://github.com/maidatagirl/Project1)

This is a project I worked on to practise my skills on Data Cleaning and Exploration.

In this project, I used Python pandas and Python Matplotlib to analyze and answer business questions. The dataset contains 187,000 records broken down by Product type, Quantity Ordered,Order Date,Product Price and Purchase Address.

I performed data cleaning by :
- checking for missing values and dropping where necessary
- adding columns(month,sales and state) by extracting from columns provided
- converting columns with wrong datatypes to the correct ones(to_datetime,to_numeric)

After cleaning and confirming, I proceeded to exploring my data and getting necessary information to answer the business questions:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer the business questions,I walked through different pandas and matplotlib methods which includes:
- merging 12 months data into a single csv file
- adding columns by extracting from given columns
- using .apply() method 
- using .groupby() to aggregate according to a category
- using .sort_values() to sort values in a descending manner
- using .unique() to the unique values in a column
- plotting bar charts and lines graphs to visualize the results
- labelling the graphs



# [Project2:Tree-census-Data_Exploration](https://github.com/maidatagirl/Project2) 

This open exploratory analysis uses Python Matplotlib and Pandas to find trends and insights in the data, and to shine a light on a tree's health status and some common tree problems.

This project uses publicly available tree census data NYC OpenData (https://opendata.cityofnewyork.us/).
