# Job Market Analysis using AmbitionBox

### Project Overview :

This project focuses on analyzing job market trends using data collected from the AmbitionBox platform. The objective is to understand how company characteristics such as sector, location, salaries, benefits, and hiring activity influence employee satisfaction and organizational performance.

The project applies web scraping and exploratory data analysis (EDA) techniques to extract meaningful insights from real-world company review data.

### Problem Statement :

Online company review platforms generate large volumes of data related to employee experiences, job availability, salaries, interviews, and organizational reputation. Due to the size and complexity of such data, it becomes difficult to manually identify trends and relationships across companies, sectors, and cities.

There is limited clarity on how factors such as:

Company sector

Geographic location

Job availability

Benefits

Salaries

impact overall company ratings and employee satisfaction.

A structured data analytics approach is required to extract insights and support informed decision-making for job seekers, recruiters, and organizations.

### Objectives :

The main objectives of this project are:

To analyze company ratings and reviews to understand overall employee satisfaction.

To examine the relationship between ratings and factors such as salaries, job availability, interviews, and benefits.

To identify sector-wise and city-wise trends in company performance.

To understand how company size and geographic presence influence workforce engagement.

### Data Source :

The data was collected from AmbitionBox, an online company review and job listing platform.

The dataset contains information on 1,778 companies, including:

Company name

Sector

City

Ratings

Number of reviews

Salaries

Interviews

Job openings

Benefits

Geographic presence

Tools & Technologies

Python

Requests

BeautifulSoup

Pandas

NumPy

Matplotlib

Seaborn

Regular Expressions (Regex)

### Methodology :

1. Web Scraping

Used the client–server architecture where Python scripts sent HTTP requests to the AmbitionBox website.

Extracted raw HTML content using the requests library.

Parsed required elements using BeautifulSoup.

Collected company-level information such as ratings, reviews, salaries, interviews, jobs, sector, benefits, and city details.

2. Data Cleaning & Preprocessing

Converted missing and inconsistent values into standardized numerical formats.

Cleaned numeric columns containing symbols such as k, l, commas, and text.

Transformed salary values into uniform numerical representations.

Extracted city names using regular expressions.

Created a new feature other_city_count to represent geographic presence.

Removed duplicate records.

Handled missing values using appropriate imputation techniques.

The final dataset is clean, consistent, and analysis-ready.

### Exploratory Data Analysis (EDA) :

Univariate Analysis

Most company ratings fall between 3.5 and 4.2, indicating generally positive employee satisfaction.

Job openings show a highly right-skewed distribution, meaning most companies have very few job postings.

A small number of companies dominate hiring activity.

Bivariate Analysis

Strong relationships were observed between:

Salaries and job openings

Interviews and job openings

Higher salary levels are generally associated with better company ratings.
Benefits show moderate correlation with salaries and reviews.

Sector & City Insights

IT Services & Consulting shows the highest salary levels, especially in Bangalore.

NBFC and Pharma sectors show stable and high employee satisfaction.

Metro cities such as Bangalore, Mumbai, and Pune consistently offer higher salaries.

Employee experience varies significantly across sectors and cities.

### Key Insights :

Larger organizations tend to offer better compensation and attract more candidates.

Salary and interview activity strongly influence employee engagement.

Ratings are weakly correlated with job count, indicating satisfaction is influenced more by workplace quality than hiring volume.

Geographic location plays a major role in salary distribution and job availability.

### Conclusion :

This project demonstrates how real-world job market data can be transformed into meaningful insights using data analytics techniques. The analysis highlights the influence of company sector and location on employee satisfaction, compensation, and hiring activity.

The project also reflects practical challenges in real datasets, such as missing values, inconsistent formats, and outliers, and shows how systematic data preprocessing enables reliable and accurate analysis.
