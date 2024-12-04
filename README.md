**#EPL Correlation Analysis**

Explore the correlation between various statistics and points gained in the 2023-24 English Premier League (EPL) season.

**Objective**
Recently, I came across a tweet highlighting the correlation between winning percentage and three-point (3P) shooting percentage in the last NBA season. The teams with the highest 3P percentages also had the highest win percentages, and no team with an above-league-average 3P percentage had a win percentage below 50%. This observation led me to wonder: is there a similar correlation in football, particularly in the Premier League?
This project analyzes the impact of key goal- and shooting-related statistics on points earned during the 2023-24 EPL season. The key metrics considered include:

Goals Scored
Goals Against
Goal Difference
Total Shots
Shots on Target
Shot Accuracy
The goal is to identify patterns and relationships that might influence team performance.

**Features**

Correlation Analysis: Assess how different statistics correlate with team points.
Visualizations: Use plots to illustrate statistical relationships.
Insights: Highlight key findings about performance metrics in the EPL.

Technologies Used
Python: For data processing and analysis.
Pandas: For handling and manipulating the dataset.
Seaborn: For creating correlation heatmaps and other visualizations.

**Getting Started**

Prerequisites
Python 3.x installed on your system.
Jupyter Notebook or an equivalent tool to run .ipynb files.

**Installation**

Clone the repository or download the project files.
Open the .ipynb file in Jupyter Notebook.

**Dataset**

The data used in this project was manually gathered from various online sources(https://www.premierleague.com/stats , https://www.whoscored.com/Regions/252/Tournaments/2/Seasons/9618/Stages/22076/TeamStatistics/England-Premier-League-2023-2024 ), and stored in the included file. It contains statistics for the 2023-24 EPL season.

**Usage**

Open the notebook in Jupyter.

Run the cells sequentially to:

Load and preprocess the dataset.
Perform correlation analysis.
Visualize relationships using plots.
Modify or extend the analysis as needed.

**Results**

This project provides insights into how various metrics affect team success in the EPL. You can replicate the analysis or use the provided code as a foundation for further exploration.

**Analysis Report**:
Correlation of Key Stats with Team Performance in the Premier League
Introduction Recently, I came across a tweet highlighting the correlation between winning percentage and three-point (3P) shooting percentage in the last NBA season. The teams with the highest 3P percentages also had the highest win percentages, and no team with an above-league-average 3P percentage had a win percentage below 50%. This observation led me to wonder: is there a similar correlation in football, particularly in the Premier League?

To investigate, I collected data on several performance metrics: Goals Scored (G), Goals Against (GA), Goal Difference (GD), Total Shots, Shots on Target, and Shot Accuracy. In the visualizations:

Red line indicates the relegation cut-off.

Blue line represents the European competition qualification threshold.

Green line is the regression line for statistical trend analysis.

Black line marks the league average.

**Findings**

*Goals Scored (G)*

Teams that scored more goals generally finished higher in the league standings. This trend is expected in a low-scoring sport like football, where each goal has a significant impact on points and positioning.

*Goals Against (GA)*

While strong defense is beneficial, it's not a guaranteed determinant of a higher league finish. For instance, Everton had the fourth-best defense but only managed a 15th-place finish. However, poor defense is more likely to lead to relegation, as evidenced by the three relegated teams, each having one of the league’s worst defenses.

*Goal Difference (GD)*

Goal difference strongly correlates with success; six of the seven teams with the best GD qualified for European competition. Similarly, the three teams with the worst GD were relegated.

*Total Shots/Shots on Target*

Teams with the fewest shots generally ended up in relegation positions, while the top three teams in shots attempted also occupied the highest league spots. This suggests a correlation between shot volume and success. The same can be said for shots on target.

*Shot Accuracy*

Shot accuracy showed some unexpected patterns. Arsenal and Liverpool, for example, finished second and third, respectively, despite being below the league average in shot accuracy. Meanwhile, Manchester City’s first-place shot accuracy aligned with their league victory. However, not all cases supported this correlation; Wolves had the fourth-best shot accuracy but only finished 14th.

**Conclusions**

*For Goals*: Scoring more goals correlates strongly with a higher league finish. Likewise, conceding fewer goals is essential to avoid relegation.

*For Shots*: Higher shot volumes appear beneficial, while shot accuracy alone doesn’t always predict better standings. Teams should focus on taking a high number of on-target shots from optimal positions on the field, as creating quality chances can be more valuable than solely improving shot accuracy.

**Acknowledgments**

Special thanks to the various sources from which the data was gathered.
