# IPL-Data-Analysis
Project Overview

This project performs Exploratory Data Analysis (EDA) on the Indian Premier League (IPL) dataset using Python. The analysis uncovers insights about team performances, match results, toss decisions, player achievements, and season-wise statistics through data visualization and statistical exploration.

Objectives
Analyze IPL match data.
Identify top-performing players based on "Player of the Match" awards.
Study the impact of toss wins on match outcomes.
Compare team performances while batting first and batting second.
Explore season-wise and city-wise match statistics.
Visualize trends using charts and graphs.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Dataset

The project uses IPL datasets containing:

Match information (ipl-dataset.csv)
Ball-by-ball delivery data (deliveries.csv)

Dataset features include:

Match ID
Season
City
Toss Winner
Match Winner
Player of the Match
Win by Runs
Win by Wickets
Team Information
Analysis Performed
1. Player Performance Analysis
Most "Player of the Match" awards.
Top 5 and Top 10 players with the highest awards.
Bar chart visualization of leading players.
2. Match Result Analysis
Distribution of match results.
Winning margins by runs.
Winning margins by wickets.
Histograms showing victory distributions.
3. Team Performance Analysis
Teams with the most wins while batting first.
Teams with the most wins while batting second.
Bar charts and pie charts for team comparisons.
4. Toss Impact Analysis
Number of toss wins by each team.
Relationship between toss winners and match winners.
Probability of winning after winning the toss.
5. Season and Venue Analysis
Matches played in each season.
Cities hosting the most IPL matches.
6. Ball-by-Ball Data Exploration
Loading and exploring delivery-level data.
Match-specific analysis using delivery records.
Visualizations

The notebook includes:

Bar Charts
Histograms
Pie Charts
Frequency Distributions

These visualizations help in understanding:

Player achievements
Team dominance
Match-winning patterns
Seasonal trends
Project Structure
IPL-Data-Analysis/
│
├── IPL-Data-Analysis.ipynb
├── ipl-dataset.csv
├── deliveries.csv
├── README.md
└── images/
Installation

Clone the repository:

git clone https://github.com/your-username/IPL-Data-Analysis.git

Navigate to the project folder:

cd IPL-Data-Analysis

Install required libraries:

pip install pandas numpy matplotlib seaborn

Run Jupyter Notebook:

jupyter notebook
Sample Insights
Identified players with the highest number of Player of the Match awards.
Determined teams with the most successful batting-first victories.
Evaluated how often winning the toss translates into winning the match.
Explored IPL match distribution across seasons and cities.
Future Improvements
Interactive dashboards using Plotly or Power BI.
Advanced predictive analytics for match outcomes.
Team-wise performance comparison across seasons.
Machine Learning models for IPL match prediction.
Author

Hrithik
B.Tech CSE (Data Science & AI)
Sikkim Manipal Institute of Technology (SMIT)
