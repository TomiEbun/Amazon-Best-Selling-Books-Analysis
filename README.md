# Amazon-Best-Selling-Books-Analysis (2009-2019)
## PROJECT OVERVIEW

**Amazon marketplace is a leading e-commerce platform for book sales since July 5th,1994.It was established by Jeff Bezos and will continue to be a leader in technological innovation, customer service, and a diverse marketplace. Amazon has revolutionized book sales and distribution by growing into one of the largest and most diverse online marketplaces in the world.**

**The impact of Amazon on the book industry and e-commerce landscape continues to grow,despite selling items other than books, such as electronics, clothing, and home goods, amazon continues to invest in enhancing its book-selling capabilities and values books as its core business.**

**In this project, I web scrapped and analyzed Amazon Best Selling Books from 2009 to 2019. I wrangled the data to find insights and patterns.The dataset for this project will  be scrapped from the Amazon website using beautifulsoup & selenium.After webscrapping the amazon website,several rows in the scraped dataset for 2009-2019 has missing and null values.**

**My first step was to check the dataset and I realized that some of the books on the website had multiple formats with different values for ( cover types). Some columns were also missing (Reviews, author and prices).However, I used Excel to fill in the missing values using the information provided on the website.**

**In data curation process which is the process of organization and integration of data collected from various sources.It was observed that Amazon best book selling  does not have a definite categorization of books on their website as one book can be found in different departments. This departments include Biographies & Memoirs,Christian Books & Bibles, Arts & Photography, Business & Money, Children's Books,parenting and relationship, medical books, Comics & Graphic Novels etc).***

**There is a need for categorizing the books in different departments into a distinct category for exploratory analysis. I checked the Goodreads website https://www.goodreads.com/ which is the world's largest site for readers and book recommendations to get the distinct category of each books.**

**I then checked kaggle for a dataset that has the tittle and distinct category (Non fiction and Fiction) of the books scrapped from amazon website for 2009-2019.This dataset will be merged with the amazon best selling books dataset scrapped from the website.**

**After doing data cleaning,each year contains a list of 100 best-selling books. The whole data contains 607 rows and 9 columns in total.**

### Metadata Description

The scrapped data contains the following columns:
title: the title of the book

genre: this is the category or type of book (Fiction or Non-Fiction)

author: this is the name of the author of a book

cover_type: this is the cover type of each book

rating: this is the user rating that a book has

price: the price of each book

rank: the ranking of each book in the top 100 best-selling for each year

year: this is the year each book appeared as a best-selling book

no_of_review: this is the total reviews a book has



## SUMMARY OF THE FINDINGS

### 1. Author BrenA Brown and Jeff Kinney are the top selling author with 14 apperences in the top selling books from 2009 to 2019.

### 2. It was observed that the gift of imperfection ,The great Gatsby and Strengths finder 2.0 has the highest number of occurence amongst the top 10 most popular books.

### 3.According to Amazon's best selling book list between 2009 and 2019, the most popular cover type is hardcover (324 titles); the least popular cover type is Mass Market paperback (13 titles)

### 4.The top outliers in the ratings variable were books that had below 4.0 ratings.
### It was observed that the outliers in the number of reviews variable is a book that had about 600,000 reviews. 
### The outlier in the price range is a book that was sold for about 140 dollars. 
### It was observed that most user ratings occured between 4.5 and 4.8,most occuring price range was between 10 and 18 dollars, and most occuring number of reviews were below 40,000.

### 5.The Amazon best book selling with Non-Fiction category was the most popular category from 2009 to 2019, with 55.13% (percent) of the 215 books being Non-Fiction and 45.6% (percent) being Fiction.

### 6.It was observed that  the highest percentage (66.7%) of Non fiction books were sold in 2017 and the highest percentage of fiction books were sold in 2009.However,the lowest percentage of books for Non fiction were sold in 2009 and lowest percentage of fiction books sold are in 2007.

### 7.Paula Hawkins and Delia Owens are the two best selling authors with the highest number of books reviews in the top 10. However, we can see that Delia Owens is that one outlier that appears to have had the most number of reviews, approximately 611,916 which is much higher than the number of reviews of other authors.

### 8.It was observed that the top 10 best-selling fiction titles received approximately 56,963 reviews on average, while the top 10 best-selling non-fiction titles received approximately 24,952 reviews on average.We can see that Fiction best-selling books received more reviews than non fiction between 2009 and 2019.

### 9.The average price of Amazon's best-selling books has decreased over the years; in 2013 it was around 17.08 dollars, but by 2019, it was approximately 11.10dollars.Overall, cost of books were decreasing with Years.

### 10.From the scatterplot,there is a negative correlation between prices and the number of reviews.This indicates that as the number of reviews increases, the price decreases slightly, but the correlation is not very strong, suggesting that the relationship is not significant.

### In other words,a correlation does not imply causation, so we cannot conclude that a decrease in prices directly results from an increase in reviews.We also observed that there are outliers in the prices of books which is  above 140 dollars and number of reviews which is above 600,000 reviews.

### 11.The top 10 amazon best selling books Authors with the highest User ratings has 4.90 stars for their books.

### 12.It can be observed that the author with highest priced books is American Psychiatric Association who charges 93.49 dollars, However,American Psychiatric Association is an outlier having the maximum price of above 80dollars.

### 13.From the amazon best books selling , the heatmap shows that year has a positive correlation with the books ratings.A strong correlation exists between the number of reviews and the year, suggesting that the number of reviews tends to increase over time, however, the other correlations are not significant enough to draw strong conclusions about their relationships.

### 14.Among the top 10 Best Selling Authors based on Genre and Number of their books appearances-Jeff Kinney and Suzanne collins rank the top two best selling authors for Fiction genre category between 2009 and 2019.The top two best selling authors in Non Fiction  genre category between 2009 and 2019 are Gallup and the College Board Authors.

### 15.Amazon top 5 best Fiction selling books based on user reviews are Where the Crawdads Sing,The Girl on the train, Eleanor Oliphant is completely fine: A novel, Beneath a Scarlet Sky and All the light we canot see. However,Where the Crawdads Sing is that outlier with the highest number of reviews of about 611,916 reviews.

### Amazon top 5 best Non Fiction selling books based on user reviews are Educated:A Memoir,Becoming,The Subtle Art of Not Giving a Fuck: A Counterintuitive Approach to Living a Good Life, Sapiens:Abrief History of Humankind.However,Where the Educated:A Memoirs is that outlier with the highest number of reviews of about 208,290 reviews.

### 16. The Word cloud for amazon best selling books provides at-a-glance view and It makes it easier to communicate the main themes or trends in huge text sets to a wider audience when they can be summarized and visualized in such an appealing and straightforward way.
