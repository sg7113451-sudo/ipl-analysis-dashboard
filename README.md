IPL Analysis Dashboard (2008 – 2025)

An interactive Power BI dashboard that analyses every IPL season from 2008 to 2025. Pick a season from the slicer and the whole report updates: champions, runner-up, key KPIs, Orange Cap and Purple Cap winners, fours and sixes leaders, and the full points table.

Project Overview

The goal of this project is to turn raw IPL match and ball-by-ball data into a clear, season-wise view of team and player performance. It covers data cleaning, data modelling and dashboard design in Power BI.

Dataset

The data was downloaded from Kaggle and consists of four files:

File	What it contains
Ball-by-ball data	Delivery-level records: runs, boundaries, batter and team details
IPL matches data	Match-level details for each season
Player data	Player information
Team data	Team information

Dataset source: <add your Kaggle dataset link here>

Dashboard Features
Season slicer to view any IPL season from 2008 to 2025
Champions and Runner-up cards with team logos
KPI cards: Total 6's, Total 4's, Total Matches, Total Teams, Centuries, Half Centuries, Total Venues
Orange Cap stats: top run-scorer, total runs and team
Purple Cap stats: top wicket-taker, total wickets and team
Most Fours and Most Sixes: player, count and team
Points Table: matches played, won, lost, no result, tie and total points for each team
Charts page: Team Wins, total runs by team, and runs split by batter type (right-hand vs left-hand bat)
Page navigation: Home, Dashboard, Charts
Screenshots

Add your screenshots to the screenshots/ folder and link them here:

![IPL 2022 Dashboard](screenshots/ipl-2022.png)
![IPL 2011 Dashboard](screenshots/ipl-2011.png)
![IPL 2024 Charts](screenshots/ipl-2024-charts.png)
Tools Used
Power BI Desktop (data modelling, measures, visuals)
Excel / CSV (source data)
Kaggle (dataset source)
Repository Structure
ipl-analysis-dashboard/
├── IPL_Analysis.pbix
├── data/
│   ├── ball_by_ball.csv
│   ├── matches.csv
│   ├── players.csv
│   └── teams.csv
├── screenshots/
└── README.md

Rename the files in data/ to match your actual file names.

How to Use
Download or clone this repository.
Open the .pbix file in Power BI Desktop.
If Power BI asks for the data location, point it to the files in the data/ folder.
Use the Season slicer to explore any year.
Author

Shubham Gaikwad GitHub: https://github.com/sg7113451-sudo LinkedIn: https://www.linkedin.com/in/shubham-gaikwad-6b1432215
