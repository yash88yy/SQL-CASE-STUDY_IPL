# SQL-CASE-STUDY_IPL

📊 IPL Players SQL Analysis
Overview
This project contains a set of SQL queries designed to analyze IPL (Indian Premier League) player auction data. The dataset (IPLPlayers) includes details such as player name, team, role, type (Indian/Overseas), and auction price (in crores).

The queries solve 10 practical problems related to team spending, player rankings, and comparative analysis.

🗂 Dataset Structure
Table: IPLPlayers

Column	Description
Player	Name of the player
Team	IPL team name
Role	Player role (Batsman, Bowler, All-rounder, etc.)
Type	Indian or Overseas
Price_in_cr	Auction price in crores


✅ Problems Solved
Q1: Team Spending
Find the total spending on players for each team, sorted by highest spending.

Q2: Top All-rounders
Identify the top 3 highest-paid All-rounders across all teams.

Q3: Highest-Priced Player per Team
Find the most expensive player in each team using a CTE.

Q4: Top 2 Players per Team
Rank players by price within each team and list the top 2.

Q5: Most & Second Expensive Players
Retrieve both the highest and second-highest priced players for every team.

Q6: Contribution Percentage
Calculate each player’s percentage contribution to their team’s total spending.

Q7: Price Classification
Classify players into High (>15 cr), Medium (5–15 cr), Low (<5 cr) categories and count them per team.

Q8: Indian vs Overseas Comparison
Compare the average price of Indian players vs Overseas players.

Q9: Above Team Average
Identify players who earn more than their team’s average price.

Q10: Most Expensive by Role
Find the most expensive player for each role using a correlated subquery.

⚡ Key SQL Concepts Used
Aggregate Functions: SUM(), AVG(), MAX()

Ranking Functions: ROW_NUMBER(), DENSE_RANK()

CTEs (Common Table Expressions) for modular queries

CASE Statements for classification

Correlated Subqueries for role-based analysis

Window Functions for percentage contribution

🚀 How to Run
Create the IPLPlayers table and insert auction data.

Run each query in SQL Server / PostgreSQL / MySQL (minor syntax changes may apply).

Analyze the results to gain insights into team spending and player distribution.

📌 Example Insights
Which team spends the most on players.

Who are the top-paid All-rounders.

Contribution of each player to their team’s budget.

Comparison of Indian vs Overseas player valuations.

🏏 Use Case
This project is useful for:

Practicing SQL window functions and CTEs.

Learning data analysis techniques with sports datasets.

Building portfolio projects for GitHub showcasing SQL proficiency.

Would you like me to also add a sample dataset (INSERT statements) so that anyone cloning your repo can run the queries immediately without needing to prepare their own table?

GIVE ONE DETAILED README
Here’s a detailed README.md you can upload to GitHub along with your SQL project. It’s structured, professional, and explains everything clearly for reviewers or recruiters:

🏏 IPL Players Auction Analysis – SQL Project
📌 Overview
This repository contains a collection of SQL queries designed to analyze IPL (Indian Premier League) auction data. The dataset (IPLPlayers) includes details about players, their teams, roles, nationality, and auction prices.

The queries solve 10 real-world problems such as team spending, player rankings, contribution percentages, and comparisons between Indian and overseas players.

This project demonstrates the use of SQL window functions, CTEs, subqueries, and aggregate functions to extract meaningful insights from sports auction data.

🗂 Dataset Structure
Table: IPLPlayers

Column	Description
Player	Name of the player
Team	IPL team name
Role	Player role (Batsman, Bowler, All-rounder, etc.)
Type	Indian or Overseas
Price_in_cr	Auction price in crores


✅ Problems Solved
Q1: Team Spending
Calculate total spending on players for each team.

Sort teams by spending in descending order.

Q2: Top All-rounders
Find the top 3 highest-paid All-rounders across all teams.

Q3: Highest-Priced Player per Team
Identify the most expensive player in each team using a CTE.

Q4: Top 2 Players per Team
Rank players by price within each team.

List the top 2 players per team.

Q5: Most & Second Expensive Players
Retrieve both the highest and second-highest priced players for every team.

Q6: Contribution Percentage
Calculate each player’s percentage contribution to their team’s total spending.

Q7: Price Classification
Classify players into:

High: Price > ₹15 crore

Medium: ₹5–15 crore

Low: Price < ₹5 crore

Count players in each bracket per team.

Q8: Indian vs Overseas Comparison
Compare the average price of Indian players vs Overseas players.

Q9: Above Team Average
Identify players who earn more than their team’s average price.

Q10: Most Expensive by Role
Find the most expensive player for each role using a correlated subquery.

⚡ Key SQL Concepts Used
Aggregate Functions: SUM(), AVG(), MAX()

Ranking Functions: ROW_NUMBER()

CTEs (Common Table Expressions) for modular queries

CASE Statements for classification

Correlated Subqueries for role-based analysis

Window Functions for contribution percentage

🚀 How to Run
Create the IPLPlayers table and insert auction data.

Run queries in SQL Server / PostgreSQL / MySQL (minor syntax changes may apply).

Analyze the results to gain insights into team spending and player distribution.

📊 Example Insights
Which team spends the most on players.

Who are the top-paid All-rounders.

Contribution of each player to their team’s budget.

Comparison of Indian vs Overseas player valuations.

Identification of star players who earn above team averages.

🏏 Use Case
This project is ideal for:

Practicing SQL window functions and CTEs.

Learning data analysis techniques with sports datasets.

Building portfolio projects for GitHub showcasing SQL proficiency.

Demonstrating ability to solve real-world analytical problems with SQL.

📌 Author
Developed by Yash  
SQL Enthusiast | Data Analyst | Cricket Fan
