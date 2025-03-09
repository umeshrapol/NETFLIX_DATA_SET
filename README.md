# Netflix Data Analysis Project

# 📘 Project Overview

This project explores Netflix’s content library to uncover insights into content trends, genre popularity, release patterns, and contributor impact. Using Python libraries like Pandas, Matplotlib, and Seaborn, we analyzed the dataset to discover meaningful patterns that can help understand Netflix’s content strategy.

# 📂 Dataset Description

File: netflix_titles.csv

Source: Netflix (via public datasets)

Contents: Information about Netflix movies and TV shows, including title, genre, release year, date added, country, director, cast, rating, and duration.

# 🛠️ What We Did (Step by Step)

#  🧹 Data Cleaning & Transformation # 

 Checked for Missing Values:  We filled in missing director and cast names as 'Unknown' to avoid losing valuable data.

Exploded Columns: Split up lists (like multiple genres, cast members, and directors) so we could count and analyze each value separately.

Converted Dates: Transformed date strings to proper datetime format for accurate time-based analysis.

#  🔍 Content Distribution Analysis

Movies vs TV Shows: Visualized the content types and found that Netflix hosts more movies than TV shows (~70% movies).

Rating Breakdown: TV-MA, TV-14, and PG-13 were the most common ratings, highlighting Netflix’s focus on mature and teen audiences.

#  🌍 Country & Contributor Insights

Top Countries Producing Content: The US, India, and the UK topped the list, showing Netflix’s global reach.

Top Directors & Actors: Identified creators like Rajiv Chilaka and David Attenborough who contributed heavily to Netflix content.

#  🎭 Genre Trends

Most Common Genres: Documentaries, stand-up comedy, and international TV shows were the most frequent genres.

Visualizing Genre Popularity: A count plot helped us easily see which genres dominated the platform.

#  📆 Release Timing Patterns

Best Time to Release Content:

Movies: Week 1 (January), peak month: July (Summer break!)

TV Shows: Week 27 (July), peak month: December (Holiday binge-watching)

Time to Reach Netflix: On average, content landed on Netflix 334 days after its initial release.

#  📊 Visualizations & Plots

We used bar charts, pie charts, and line plots to make the data more understandable. For example, visualizing the top 10 contributing countries helped us quickly see the global distribution of Netflix content.

# 🛠️ Tools & Libraries Used

Python: For all data analysis

Pandas: Data manipulation and transformation

Matplotlib & Seaborn: Data visualization

Jupyter Notebooks: For interactive exploration and coding

# 📌 Key Takeaways

Netflix relies heavily on mature and teen content (TV-MA & TV-14).

The platform sources content globally, with the US and India leading the way.

Timing matters: Content releases spike in summer and holiday seasons.

Licensing Strategy: Most content arrives on Netflix about a year after its initial release.

# 🚀 Final Thoughts

This project provided a thorough understanding of Netflix’s content landscape. By breaking the data into digestible parts and visualizing trends, we gained valuable insights into what makes Netflix’s library so diverse and appealing to audiences worldwide.

If you’d like to dig deeper, run the .ipynb file to see all the code and experiment with the data yourself!

Let me know if you want me to refine anything further! 🚀
