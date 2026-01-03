## Project Report: Exploratory Data Analysis of Cricket World Cups (1975–2019)
Objective

The aim of this project is to perform an in-depth exploratory analysis of Cricket World Cup data spanning from 1975 to 2019. The dataset includes comprehensive information about each tournament edition, such as match details, participating teams, venues, and results. The project involves loading the data into a Jupyter Notebook, storing it in a MySQL database, and conducting various analytical and visualization tasks to reveal meaningful insights and patterns in the World Cup history.

1. Data Import and Database Setup

The first phase of the project focused on importing the raw data from multiple CSV files into the Jupyter Notebook environment. Each CSV file corresponds to a different World Cup edition from 1975 to 2019. After successful import and initial inspection, the data was loaded into a MySQL database using the SQLAlchemy library to support efficient querying and further analysis.

2. Data Cleaning and Transformation

To ensure accurate, reliable analysis, the dataset underwent extensive cleaning and transformation. Key steps included:

Converting date fields into standard datetime format for consistency.

Correcting inconsistent or missing values.

Adjusting data types to appropriate formats.
This cleanup process was essential to enhance data quality and prepare it for meaningful analysis.

3. SQL Queries and Insights

A series of SQL queries were executed on the MySQL database to extract useful information and answer analytical questions. Some key queries included:

Query 1: Total number of matches played in all World Cups.

Query 2: Number of matches played at each venue.

Query 3: Detailed summary of the 1983 World Cup final.

Query 4: Count of matches won by each team across all tournaments.

These queries helped uncover patterns and trends that form the basis for deeper insights into World Cup history.

4. Data Visualization

To make the insights easily understandable and visually appealing, several visualizations were created using Matplotlib and Seaborn. These visualizations helped in illustrating trends and drawing comparisons. Examples include:

Bar charts showing the total number of wins by each team.

Heatmaps depicting match outcomes.

Distribution charts illustrating how frequently teams played at different grounds.

Win percentage visualizations to explore team performance.

These graphs and charts brought clarity to the patterns observed in the data.

5. Key Findings

The analysis revealed several interesting insights:

Total Matches: The total number of games played in each World Cup edition was calculated, showing growth over time.

Match Distribution by Grounds: Some venues hosted significantly more matches than others, highlighting popular cricket stadiums.

1983 World Cup Final: Details of the final match were extracted, providing information on participating teams and the result.

Team Performance: A summary of team wins highlighted dominant teams over multiple tournaments.

6. Conclusion

The exploratory data analysis successfully uncovered valuable insights from historical Cricket World Cup data. By importing and cleaning the dataset, building a structured database, executing analytical SQL queries, and creating informative visualizations, the project delivered a comprehensive view of tournament trends and team performances over time. The results shed light on important aspects of World Cup history and provided a strong foundation for further investigation.

7. Future Work

This project lays the groundwork for more advanced analyses. Potential future extensions could include:

Player-level analysis to evaluate individual performance statistics.

Time-based performance trends to examine how teams evolved across tournaments.

Correlation studies to find relationships between match conditions and outcomes.

Machine learning models to predict match results using historical trends and features.
