Netflix Data Analysis Dashboard

*📌 Project Overview*
This project is an interactive Netflix Data Analysis Dashboard built using Power BI. It provides insights into Netflix's content library, including movies and TV shows, across different countries, genres, ratings, and release years.

The dashboard helps in understanding content distribution, trends, and key metrics in a visually appealing and user-friendly way.

*📊 Key Features*
- *Total Titles Overview*
    - Total Titles: 9K+
- *Content Type Split* → Movies vs TV Shows
- *Top 10 Countries* → By content count
- *Genre Distribution* → Most popular genres
- *Release Year Trend* → Content added over time
- *Rating Analysis* → TV-MA, PG-13, etc.
- *Director & Cast Insights* → Top contributors

---

*But important:* Before Power BI, you need the data in MySQL.

*Next steps to type in MySQL Workbench after Server works:*
CREATE DATABASE netflix_db;
USE netflix_db;

CREATE TABLE netflix_titles (
    show_id VARCHAR(10),
    type VARCHAR(20),
    title VARCHAR(300),
    director VARCHAR(500),
    cast VARCHAR(1000),
    country VARCHAR(200),
    date_added VARCHAR(50),
    release_year INT,
    rating VARCHAR(20),
    duration VARCHAR(50),
    listed_in VARCHAR(300),
    description TEXT
);

Then you’ll import the Netflix CSV file.

*First tell me: MySQL Server start zala ka?* Port 3307 var green tick aala? If not, dashboard banavnar nahi. Server fix karu ya first.
