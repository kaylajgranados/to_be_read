# TBR (to be read) Goodreads Data 

# Background 

This project represents one evening spent writing Python pandas code to analyze my Goodreads "To Read" list. I plan on revisiting this to add matplotlib visualizations and clean up the code. 

As an avid reader, I found myself with over 500 books shelved as "To Read" in Goodreads. It became challenging to sort through this list to find my next read. I'm hoping to use my Python skills to solve this problem. 

# Dataset 

This dataset was exported from Goodreads. I manually removed the "Read" books from the excel sheet before beginning the analysis. 

# Data Cleaning 

* Dropped columns not needed for analysis
* Checked for duplicates

# Data Analysis 

* Average Rating: 4.01
* Average Page Number: 366
* Median Publication Year: 2015
* Max Page Number: 1327
* Max Rating: 4.88

# Data Manipulation

I categorized Average Rating, Number of Pages, and Original Publication Year into bins based on percentiles.

<img width="639" alt="Screen Shot 2025-02-20 at 8 13 19 PM" src="https://github.com/user-attachments/assets/7809bdd4-5335-4e4b-978f-e62541212e25" />

This enabled me to filter the dataset to match certain criteria. 
* I started with Very High Rating, which resulted in 111 rows. 
* Then, I tried Very High Rating and Very Recent Publication Year, still giving me 25 rows. 
* Finally, when I filtered by Very High Rating, Medium Page Length, Very Recent Publication Year, I had two books to chose from. 

<img width="1132" alt="Screen Shot 2025-02-20 at 8 16 39 PM" src="https://github.com/user-attachments/assets/4214feac-bac9-4aac-8ab7-14fb13866e5d" />



I next filtered for books with a Very High Rating, Very High Page Length, and Very Early Publication Year, which produces 5 options very different than the previous search results. 

<img width="1128" alt="Screen Shot 2025-02-20 at 8 17 57 PM" src="https://github.com/user-attachments/assets/6aefb4ec-aef3-4bdb-9d4c-cacd4efc22bc" />

# Conclusion

These filters can be used to narrow down book options based on rating, page number, and publication year in a much more efficient way than scrolling through 500+ books on Goodreads.  I'm excited to continuing playing around with this data and enjoying the books! :) 


