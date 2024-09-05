# Sales Analysis in different Metrics using Python



# Problem Statement



This analysis aims to uncover insights into customer behavior and sales performance across various demographic and transactional parameters. By leveraging key features such as customer demographics (Gender, Age, Marital Status, State, Zone, Occupation), product information (Product ID, Product Category), and transaction data (Orders, Payment Mode, Amount), the objective is to identify trends and patterns in sales. 

The study will employ visualizations to evaluate sales performance based on customer segments, product categories, and payment modes, providing actionable insights for improving sales strategies and enhancing customer targeting.


# Objectives

1) Analyze Sales Performance: Evaluate overall sales performance by segmenting data based on key customer demographics such as Gender, Age, Marital Status, State, and Occupation.

2) Identify Top-Performing Products: Investigate product categories to determine which products generate the highest revenue and have the most orders across different customer segments.

3) Understand Payment Mode Preferences: Assess the distribution of payment modes to identify the most popular payment methods and their correlation with sales and customer demographics.

4) Visualize Regional Sales Trends: Analyze sales distribution across different states and zones to identify regional patterns and opportunities for targeted sales strategies.

5) Optimize Customer Targeting: Leverage insights from customer behavior, including age groups and occupations, to enhance product recommendations and marketing efforts for different segments.

# Steps followed 


- Step 1 : Load data into Jupyter Notebook, dataset is a csv file.
  
- Step 2 : Create New file & Load required libraries (Numpy, Pandas, Matplotlib.pyplot, seaborn, etc)
  
- Step 3 : Create dataFrame for analysis.
  
- Step 4 : Examine Data - This include getting information about dataset, Dataset Shape, Data type of columns in dataset.
   
- Step 5 : Data Cleaning & Preprocessing - This step include Removing Null Values from dataset, Removing unwanted columns & 
           changing data types of required columns.
  
- Step 6 : Firstly we analyze data based on Gender. for which we have shown following cases
            i) Number of Customer base on Gender
           ii) Then we created age groups bins
          iii) find male/femal in age group
           iv) Total Sales According to Different Age Group
            v) Most Popular Product by age group (we used sum of orders count for this)

- Step 7 : we find revenue & total orders by product_category
  
- Step 8 : we find sales based on Marital_Status
  
- Step 9 : we find sales & orders based on Region (Zone, state)
             i) find top 10 states based on Higher number of orders.
            ii) Find top 10 states based on Higher revenue.
           iii) Find revenue & Orders based on Zones & states
  
- Step 10 : we find sales based on occupation of Customers

- Step 11 : find Product that Purchased most of the time we find this using product_id

- Step 12 : find Transaction Mode that is mostly used & found reveneu generated from each Mode

           
# Insights
1) Most of Customers are Female(7754) & men are (3390).
2) Most of the customers that arrive are from age group (26-40) & most of them are female.
3) Highest Purchasing Age Group is from age(26-40) & they create revenue of 5,34,24,971.
4) Most Popular Product Category in age group (26-40) is Clothing & Apparel.
5) Most Popular & High Revenue Generating Product Category among all age group is Food which generate revenue about 33840126.
6) Most Unpopular & Low Revenue Generating Product Category among all age group is office & Generate revenue about 81936.
7) Most of The customers arriving have marital status as unmarried.
8) Most of the orders come from Uttar Pradesh state & it's highest contributing state in case of revenue & Orders, while Gujrat is at 10 th position in case of orders & Revenue, among Top 10 States.
9) Most of the customers are coming from IT sector, Customers from Healthcare Sector are on second position &  Customers from Aviation Sector are on Third position
10) Mostly Used Transaction mode is Points.

# Conclusion - 
Unmarried women from age group 26-40 yrs from UP, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category.


