I conducted an in-depth exploration and analysis of the T20 Cricket World Cup 2022 data. The project involved web scraping data from ESPN Sports website using Python, followed by data transformation and validation to ensure precision and reliability. The analyzed data was then visualized using Power BI to create an interactive dashboard.

The primary objective of this project was to extract meaningful insights and trends from the T20 Cricket World Cup 2022 data. This encompassed team performance, individual player statistics, and match outcomes. By employing advanced analytical techniques and visualization tools, I unveiled concealed patterns and relationships in the data, providing valuable insights to cricket enthusiasts and industry professionals alike.

The code and documentation in this repository offer a comprehensive account of my data analysis process. It covers web scraping, data cleaning, visualization, and dashboard creation. This repository serves as a valuable resource for those seeking to delve into data analysis and visualization within the realm of cricket sports.

The data is sourced from the following website: 
 
https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?id=14450;type=tournament

Four primary categories of data were acquired through web scraping:
a) match_summary: Extracted directly from the table provided in the link.
b) batting_summary: Obtained from scorecard column links, containing comprehensive batting information for each match.
c) bowling_summary: Acquired using similar methods as batting_summary, but focusing on bowling data.
d) player_info: Extracted from player name links within each scorecard link, with duplicates cleaned during the iteration process.

My cricket data analysis project features a diverse range of visualizations within three main categories: Tournament Stats, Batting Stats, and Bowling Stats.

The Tournament Stats visualization offers insights into factors such as top runs, leading wickets, highest individual match scores, highest team inning scores, most team victories, total 4's and 6's, final match details, and venue locations. These statistics are presented in a user-friendly manner, providing quick access to crucial tournament information.

Batting Stats and Bowling Stats visualizations are further divided into three sub-categories each. Batting Stats includes Top Order, Middle Order, and Lower Order, while Bowling Stats consists of Fast, Medium, and Spin categories. Each of these subdivisions showcases top batting or bowling performances based on specific cricket filters commonly used by experts.

By categorizing the visualizations in this manner, users can easily locate specific information they seek. Whether analyzing top-performing batsmen or bowlers, or gaining a comprehensive understanding of the tournament, these visualizations offer comprehensive and easily interpretable insights.
