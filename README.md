# IPL2024-Review | Stadium Stats: Decoding-IPL-2024-Heroes
This repository showcases a data analysis project involving web scraping, data cleaning, data transformation, and dashboard creation using tools like Excel and Power BI.
This repository demonstrates a detailed data analysis project focused on cricket statistics, particularly exploring batting and bowling performances in the IPL (Indian Premier League). The project involved data collection, cleaning, transformation, and the creation of an interactive Power BI dashboard.

# Data Collection
Data was collected through web scraping using:
- Instant Data Scraper (Microsoft Edge Extension)
- Octoparse 8
These tools were employed to extract match and player-related statistics from online sources.

# Table Names
The cleaned data was structured into four tables:
1. Dimension Tables:
- dim_matchSummary: Contains high-level match details such as team names, match dates, and match results.
- dim_players: Includes player information such as player names, teams, and batting styles.
2.Fact Tables:
- fact_batting_summary: Holds batting-related metrics such as total runs, balls faced, batting average, strike rate, and boundary percentage.
- fact_bowling_summary: Captures bowling-related metrics such as total overs bowled, wickets taken, economy rate, and strike rate.
These tables are linked using the match_id column to establish a relational database structure.

# Data Cleaning Process
The raw data underwent the following steps for cleaning:
- Removal of duplicate entries and incomplete rows.
- Formatting of date and numeric fields to ensure consistency.
- Standardization of categorical values such as player roles and team names.
- Validation of relationships between match and player records using match_id.
- Data was divided into dimension and fact tables for easy transformation and visualization.
- The cleaned data was prepared in Microsoft Excel before being imported into Power BI.

# Dashboard Design
An interactive dashboard was created in Power BI to visualize insights. Key design features include:
1.KPIs (Key Performance Indicators):
- Batting Average
- Boundary Percentage
- Strike Rate
- Average Balls Faced

2.Visualizations:
- A line chart comparing Total Runs vs. Boundary Runs by teams.
- A scatterplot depicting Batting Average vs. Strike Rate for players.
- Tabular data for individual player statistics with metrics like batting style, total runs, balls faced, and boundary percentage.

3.Interactive Filters:
-Role-based player categorization such as power hitters, anchors, and finishers.

# Insights
1.Team Analysis:
Teams with the highest contributions to total runs are prominently visible, with a significant gap among low-performing teams.
2.Player Performance:
Players like Travis Head and Phil Salt demonstrated exceptional strike rates and high boundary percentages, making them key contributors to their teams.
3.Batting Averages:
Left-handed batters like Abhishek Sharma stood out with consistent performances and higher averages.
4.Boundary Dependency:
Teams with higher boundary percentages showed stronger batting metrics, emphasizing the role of aggressive playstyles.

![Screenshot 2024-11-27 181039](https://github.com/user-attachments/assets/2c3dd1db-589e-4ffa-82ab-72f490df21d9)

![Screenshot 2024-11-27 181150](https://github.com/user-attachments/assets/1ebd8b07-9f3e-42e6-aeb1-249b51023bcb)

![Screenshot 2024-11-27 181223](https://github.com/user-attachments/assets/19cfe103-13d9-4d40-8ded-4455e67d9bba)

![Screenshot 2024-11-27 181252](https://github.com/user-attachments/assets/b0bcc7e9-e90a-463e-a366-141bd64e53ca)

![Screenshot 2024-11-27 181315](https://github.com/user-attachments/assets/d0b921ea-0d47-4925-b5dd-61b1b6ab903c)


# Summary
This project highlights the power of integrated tools and processes, from data collection to visualization:
- Web scraping tools like Instant Data Scraper and Octoparse efficiently captured the required data.
- Excel and Power BI enabled effective data cleaning, transformation, and analysis.
- The interactive dashboard provides actionable insights into team and player performances, catering to cricket analysts and enthusiasts alike.
- Based on the analysis, the top N players were identified using a combination of custom measures such as batting average, strike rate, and boundary percentage.
-These players were recognized as standout performers, contributing significantly to their team's success.


