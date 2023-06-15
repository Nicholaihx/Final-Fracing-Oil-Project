# Final-Fracing-Oil-Project
Final project for Data Analytics Diploma at SAIT 

SAIT-Final Capstone Project.pptx is a power point presentation for my final project to complete the Data Analytics program at SAIT
Some information redacted for privacy and language used in this readme is done on purpose to not name Operator Names
All data was requested to be "Normalized for time" This meant creating new columns and calculating amounts as if all wells were fully opperational without any downtime.
Please go through the Power point before coming back for explination of each dashboard below

1. Number of Stages
2. Complete Length
3. Completion Overview
4. Casing Sizes
5. Output
6. Water Cut
7. Cumulative Water Overview

Dashboard Explanations:

1. Number of Stages:
  Four scatter charts showing the comparison of number of fracing stages and the following four parameters
    1. Total Proppant used
    2. Average Daily Production of Oil (by barrel)
    3. Total Frac Fluid Used
    4. Completed Length
  Two Scatter charts on the left show a linear regression with a positive slope. This could be because the fluid used (proppant or total frac fluid) increases as the well increases in size. We can see this happening clearly in the Number of Stages Vs. Completed length 
 Each dot represents a unique well, colour categorized by operator name.
We can see a few patterns within these charts - many companies keep their total proppant, number of stages, and total frac fluid low to keep profits high. What is ideal to see is a low number in Total Proppant, Total Frac Fluid while keeping the Average Daily Production of Oil high. This is seen in the Navy Blue dots on each chart. This company also seems to have the longest fracing wells (See Number of Stages vs. Completed Length in bottom right)

The slicer can be adjusted to see over time but we were tasked with focusing on the first 90 days of production.
The Card shows total number of Unique Wells examined.

2. Complete Length
  Four scatter charts using Completed length to compare against the following:
    1.  Average Water cut
    2.  Daily Average Production of Oil (by the barrel)
    3.  Average Proppant used
    4.  Total Frac Fluid used
   For many of these charts, it is ideal for the completed length (all x-axis on all charts) to be smaller since it costs more money to increase the wells size. It is also ideal for increase profit to have average water cut, average proppant and total frac fluid to be low since all of these items cost a company more money for materials. We can see again, the Navy Blue dots keep their production consistantly high. Some of their wells are significantly longer than others. And have consistantly low materials used.
   
The slicer can be adjusted to see over time but we were tasked with focusing on the first 90 days of production.
The Card shows total number of Unique Wells examined.

3. Completion Overview 
  Bar Charts comparing each operators average material useage to their average completed length. Many operators seem to have similar parameters for material usage, frac spacing and number of stages. 
  The chart on the right shows average completed length at a given operating time period (slicer below chart can change the time length in months)
  
4. Casing Sizes
  Two charts comparing different casing sizes used per operator. The top chart looks at monthly average production of Oil (3 months on the slicer but can be changed to view more. Bottom Chart looks at Daily production (Note the different values on the Y-Axis). Comparing within each chart shows what companies have tried different approaches with their wells. Some have used multiple casing sizes. Only one company uses the 222 casing sizes. 
Note the Navy Blue colour - Its the same company that had high production in the first two dashboards.

5. Output
  This dashboard shows each month amounts of oil produced, water used, and barrels of oil equivalent. The bars show monthly quantities.
  Lines represent the same but averages of daily amounts. The chart shows results over 6 months. The lower right hand slicer can increase or descrease that time. The Slicer in the top right can drill into the data to isolate each Operator. 
  
6. Water Cut
  These charts examine an increased number of wells. Line and clustered column chart visualizes each Operator and their monthly production, total water used and their precentage of water cut. Analyzing the frac fluid pumped per stage vs avg water and total proppant pumped show a relationship. Operators pumping a higher amount of total frac fluid per well (1-2k) proppant (5-12 tonnes/per stage) were lower water cut percentages than operators pumping total frac fluids of (6k) proppant(15-20 tonnes/per stage).
Top right hand corner shows average water cut - can be sliced for each operator 
The slicer can be adjusted to see over time but we were tasked with focusing on the first 90 days of production.
The Card shows total number of Unique Wells examined.  
  
7. Cumulative Oil and Water
   This chart compares the usage of water, the percent of water cut and the total production over a set period of time (can be changed using the slicer on the far right.
   
8. Overview
  Just a basic table comparing operators and each of their averages over each well. We didn't want summary for anything, since some operators hold far more wells than others. 
