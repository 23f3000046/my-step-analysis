# My Weekly Step Tracking Analysis

## Overview
This document presents an **analysis** of my daily steps over the past week, comparing my activity patterns over time and with friends.

## Daily Step Counts

Below is a summary of my *daily step count* for the past week:

| Day       | Steps  | Goal Met |
|-----------|--------|----------|
| Monday    | 8,542  | Yes      |
| Tuesday   | 6,781  | No       |
| Wednesday | 9,234  | Yes      |
| Thursday  | 7,890  | Yes      |
| Friday    | 10,456 | Yes      |
| Saturday  | 12,345 | Yes      |
| Sunday    | 5,678  | No       |

```sql
-- Required SQL analysis
SELECT 
    day,
    steps,
    CASE WHEN steps >= 8000 THEN 'Yes' ELSE 'No' END AS goal_met
FROM weekly_steps;
Strikethrough Example <!-- NEW SECTION -->
My initial goal was ~~10,000~~ steps daily, but I revised it to 8,000 after realizing this was too ambitious.

Weekly Comparison
Week 1: 52,468 steps

Week 2: 58,926 steps

Week 3: 60,926 steps(current week)

Progress Tracking
My fitness goals:

Walk at least 8,000 steps for 5 days

Complete one 10,000+ step day

Maintain 9,000 daily step average

Beat my friend Sarah's weekly total

Friend Comparison
I was ~~last~~ third in my friend group this week!

Visit My Fitness Dashboard to see more detailed analytics.

Personal Insights
Walking more on weekends significantly boosts my weekly averages. I should focus on maintaining consistency throughout the week rather than relying on weekend activity spikes.

Technical Notes
The step data is processed using the calculateAverage() function in our analytics system.
