# RCB-Analysis-Project-SQL

## Problem Statement 
Hired as a sports data analyst by the Royal Challengers Bangalore (RCB) franchise. The team aims to build a strong and competitive squad for the IPL by identifying top-performing, realible and value for money players.
Using the data from the pervious 4 season the goal is to identify the weakness in team performance and create a data-backed auction strategy.

## 🎯 Objectives
- Analyze player performance across multiple IPL seasons using batting and bowling metrics such as runs, strike rate, and wickets.
- Evaluate team performance (RCB) across seasons by examining total runs scored, matches won, and year-on-year improvements.
- Identify high-performing and consistent players by comparing individual performance against overall averages.
- Assess the impact of external factors such as venue and bowling style on player performance.
- Generate data-driven insights to support team selection strategies and optimize player auction investments.

## Dataset 
- The dataset consists of 19 tables covering player and match-level statistics.
- Covers player performance across season 13-16.
- Total players - 469
- Total Matches played - 255

## Tools Used
- SQL (data querying, joins, aggregations)
- Excel (Pivot Tables for summarizarion, charts for visualization)
- Power Point (presenting insights and recommendatons)

## Approach / Methodology
- Wrote SQL queries using JOINs, GROUP BY, CTEs, and window functions to analyze player and team performance across seasons.
- Analyzed player performance treand across IPL season 13-16.
- Evaluated team wins and losses by venue to assess venue based performance patterns.
- Measured player consistency by calculating average runs scored and average wicket taken across all 4 seasons.

## Insights / Findings
*Top Performers (Batting)*
- V Kohli led all batsmen with the highest average runs scored across seasons (618.00), followed by DA Warner (587.00) and AB de Villiers (492.00)
- LMP Simmons posted the highest single-season batting average among all players (42.82), ahead of V Kohli (39.87) and DA Warner (38.49)

*Top Performers (Bowling)*
- DJ Bravo was the most consistent wicket-taker, averaging 34.00 wickets — the highest among all bowlers analyzed
- JP Faulkner (33.00) and R Vinay Kumar (27.00) followed as top wicket-takers

*Consistency*
- V Kohli, DA Warner, and AB de Villiers were the most consistent performers across all 4 seasons, each maintaining both a high scoring average and a strong wickets/seasons-played ratio
- RG Sharma stood out as a consistent all-round contributor with 474.75 average runs and 13.75 average wickets across 4 seasons

*Venue Impact*
- RCB played the highest number of matches at their home ground, recording their best win rate there: 16 wins, 11 losses, and 2 ties
- This makes the home venue RCB's strongest-performing ground based on match outcomes

*Season-wise Team Trend*
- Season 13: 9 wins, 7 losses
- Season 14: 5 wins, 9 losses (weakest season)
- Season 15: 8 wins, 6 losses
- Season 16: 9 wins, 7 losses
- RCB's performance dipped sharply in Season 14 but recovered in the following two seasons, ending on a stronger note by Season 16


