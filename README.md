# **IPL Analysis Dashboard 2008-2025**    

## **1.Executive Summary :**    
The goal of this project is to develop a comprehensive and interactive IPL Analysis Dashboard that provides a deep dive into the Indian Premier League's historical data & Current data(2008–2025).This dashboard will centralize 18 years of player data,match results,player statistics, and team performances into a single visual interface.  
By transforming millions of data points—from ball-by-ball records to season-wide summaries—this project enables cricket enthusiasts and analysts to identify winning patterns, track player consistency, and understand the impact of external factors like toss decisions and venue conditions.      

## **2.Problem Statement :**      
●Background:      
The IPL generates massive amounts of data every season. However, this data is often scattered across multiple CSV files (Matches and Deliveries), making it difficult for fans or analysts to see the "big picture" of a player’s career or a team’s journey.Manually comparing player performance across a decade or understanding the impact of toss decisions in specific venues is time-consuming and difficult without a centralized visualization tool.      
●Objective:         
To create a single, unified dashboard that allows stakeholders to:        
•Analyze player and team performance trends over 18 years.        
•Evaluate the impact of match conditions on winning probabilities.        
•Analyze individual player performance (Orange/Purple Cap races).       
•Evaluate team dominance across different seasons.      
•Compare head-to-head records between legendary rivalries.        

## **3.Scope of the Dashboard :**      
The dashboard will be divided into two primary views:         
●Season Insights (Overview):         
•Total matches played, runs scored, and wickets taken per season.      
•Finalist and Winner tracking with dynamic team logos.      
•Boundary trends (6s and 4s) across different eras of the IPL.      
●Batter & Bowler Performance:      
•Orange Cap and Purple Cap winners’ year-on-year stats.      
•Slicers for player name, team, and season.   

## **4.Methodology:**    
The project was executed through a systematic workflow:    
•Data Cleaning (Power Query): Handled missing values.   
•Advanced DAX Calculations: Created custom measures for:    
Batting: Most 4s/6s & Runs.      
Bowling: Wickets.      
•Visualization Design: Developed a dashboard.    
Season Overview: High-level trends and champions.    
Player Insights: Deep dive into individual "MVP" performances.    

## **5.Key Features:**    
•Dynamic Filters: Slicers for Season (2008–2025), Team Name, Player Name.  
•Season Highlights: Automated recognition of Orange Cap (most runs) and Purple Cap (most wickets) for each year.    

## **6.Project Roadmap (Phases):**  
•Data Acquisition: Gathering ball-by-ball and match-level datasets updated for 2025.    
•DAX Development: Writing measures for dynamic titles, winning streaks.  
•Testing & Deployment: Validating 2025 stats against official sources and publishing to Power BI Service.  

## **7.Tools and Technologies:**    
•Power BI: The core platform for data modeling and visualization.    
•Power Query: Used for complex ETL (Extract, Transform, Load) processes.    
•DAX (Data Analysis Expressions): For creating advanced cricket metrics and KPIs.    
•Excel/CSV: As the primary data sources for historical records.    
•GitHub: For project hosting and documentation.   

## **8.Expected Outcomes:**    
•Interactive Insights: A user-friendly tool for exploring 18 years of cricket history without technical skills.    
•Data-Driven Storytelling: A clear narrative of how IPL has evolved from 2008 to 2025.        
•Holistic View: A 360-degree view of IPL history without manually browsing hundreds of scorecards.      
•Engagement: Highly interactive slicers (Season, Team, Player) that allow for personalized data storytelling.      
•Strategic Planning: Helping team managers identify "anchors," "finishers," and "power hitters" based on historical data.      

## **9.Risks and Challenges:**  
•Data Inconsistency: Team names and player names may vary across datasets (e.g., "S.K. Raina" vs "Suresh Raina").  
•Challenge: Large dataset size (Deliveries.csv has 200,000+ rows).    

## **10.Conclusion:**      
This project is more than just a scoreboard; it is a comprehensive analytics tool that bridges the gap between historical legacy and modern-day T20 strategies.IPL Analysis Dashboard bridges the gap between raw cricket statistics and meaningful insights.It serves as a powerful tool for anyone looking to understand the dynamics of T20 cricket through data.By simplifying complex ball-by-ball data into visual narratives, this project highlights the power of Business Intelligence in the world of sports analytics.  


