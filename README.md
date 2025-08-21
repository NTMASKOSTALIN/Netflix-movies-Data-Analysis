# Netflix-movies-Data-Analysis
Project Objective:
To perform an end-to-end analysis of Netflix’s movie catalog (~10k rows) using Python and Tableau. The project explores genre distribution, popularity trends, and audience engagement patterns, with the goal of extracting actionable insights and presenting them visually for business decision-making.

Dataset used
- <a href="https://github.com/NTMASKOSTALIN/Netflix-movies-Data-Analysis/blob/main/mymoviedb.csv">Dataset-Python
- <a href="https://github.com/NTMASKOSTALIN/Netflix-movies-Data-Analysis/blob/main/cleaned_mymoviedb.xlsx">Dataset-Tableau
- 
Questions(KPI):
1. What is the most frequent genre released on Netflix?
2. Which genre has received the highest votes?
3. Which movie has the highest popularity, and what is its genre?
4. Which movie has the lowest popularity, and what is its genre?
5. Which year had the most movies released?
6. What is the share of each genre on Netflix?
7. What is the trend of average popularity per year?

Dashboard:
<img width="1841" height="775" alt="Bar Chart" src="https://github.com/user-attachments/assets/663032db-bd3d-4062-8318-b5ed24b7f6d9" />
<img width="1841" height="775" alt="Bar Chart 2" src="https://github.com/user-attachments/assets/43d600e1-b040-4fa8-835b-c8667c4e391b" />
<img width="703" height="775" alt="Text Table" src="https://github.com/user-attachments/assets/0a37f427-315d-485c-9db8-4b99279fb759" />
<img width="703" height="775" alt="Text Table 2" src="https://github.com/user-attachments/assets/b4a49cc0-d3dc-4cb9-8a27-4797b9daaefd" />
<img width="1841" height="775" alt="Histogram" src="https://github.com/user-attachments/assets/5aacfd11-bb2a-4aaa-a79d-827f865900c7" />
<img width="1823" height="774" alt="Pie chart" src="https://github.com/user-attachments/assets/d948cf31-e013-4050-a471-2ae890adc853" />
<img width="1841" height="774" alt="Line chart" src="https://github.com/user-attachments/assets/ad9a9de1-bfcb-425d-a1ef-b7bc8b0f3941" />

Process:
* Data Preparation
Cleaned Genre column (removed commas/white spaces).
Converted Release_date into proper datetime and extracted year.
Dropped non-relevant columns (Overview, Poster URL).
Handled outliers in the Popularity column for accurate analysis.
* Exploratory Data Analysis (Python)
Grouped data by genre, release year, and language for frequency and vote distribution.
Used Pandas and visualization libraries to analyze trends.
* Visualization (Tableau)
Pie charts for genre distribution.
Bar charts for most frequent genres and genres with highest votes.
Highlight tables for movies with max/min popularity.
Line chart showing popularity trends over time.

Project Insights:
Genre Dominance: Drama is the most frequent genre, highlighting Netflix’s strong focus on storytelling-based content.
Audience Engagement: Action and Adventure genres recorded the highest votes, showing greater viewer interaction.
Popularity Outliers: The most popular movie significantly outperformed others, while some movies/genres had extremely low popularity.
Release Growth: Movie releases surged post-2015, aligning with Netflix’s rapid global expansion.
Genre Share: Drama and Comedy form the majority of Netflix’s catalog, while genres like Horror and Documentary remain niche.
Popularity Trend: Average popularity has steadily increased year-over-year, reflecting rising global engagement with Netflix movies.

Final Conclusions:
Netflix continues to rely heavily on Drama and Comedy for volume, but Action and Thriller genres deliver stronger audience pull.
The spike in releases after 2015 aligns with Netflix’s international growth strategy.
Increasing average popularity over the years confirms that Netflix’s content strategy is successfully engaging more viewers.
Business Recommendation: Netflix should expand high-engagement genres (Action, Thriller) while retaining its dominance in Drama and Comedy to balance both quality and audience demand.
