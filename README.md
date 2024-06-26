# Web-Scraping
Book Store Web Scraping

Web scraping is not easy. It is full website that have 404 messages popping up, a sign that website builders are blocking code from web crawling. 

This topics covered in the code:
- What is the total number of books available on the website?
- How many books are there in each category?
- What is the distribution of book ratings?
- What are the top 10 highest-rated books and their prices?
- Bar chart to show the number of books in each category.
- Histogram showing the distribution of book prices.
- Scatter plot showing the relationship between book prices and ratings.
- Save book categories to CSV.

1. Load libraries

In addition to loading the Python libraries, this is the important part of the step in gaining access to the websit and in understanding website structure.

2. Data Collection and Exploration

You may notice that I am using a 'User-Agent'. This helps my code to web crawl and trick the website that I am real user, not an automated web scraper. Web scraping is helpful for a lot of use cases (e.g. stock market analysis, job board monitoring, news analaysis). But the problem is that many of these websites also use tools to block would-be web scrapers.

Q1. What is the total number of books available on the website?
This shows the data scientist that 1000 books are available. 
You will also notice that I created an error message in my function to warn me if I cannot access the website (this small addition took me some time to figure out, which should save you the time.)

Q2. How many books are there in each category?
This shows all the categories and how many books are in each category.

3. Data Analysis

Q3. What is the distribution of book ratings?
This analysis shows that most of the books have a 1-star rating.

Q4. What are the top 10 highest-rated books and their prices?
We want to find out the top 10 books (titles, ratings, and price).

4. Visualization

Q5. Bar chart to show the number of books in each category
This bar chart shows the distribution of books by category, in reverse alphabetrical order.

Q6. Histogram showing the distribution of book prices
This histogram shows that many books for sale above 40 pounds sterling.

Q7. Scatter plot showing the relationship between book prices and ratings
This scatter plot shows no relationship between book prices and ratings.

Q8. Save book categories to CSV
We can save the categories in a dictionary to store in a CSV file.

