# Movie Dashboard – Genre, Rating, and User Demographics Analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Information](#dataset-information)
3. [Project Objectives](#project-objectives)
4. [Key Questions Answered](#key-questions-answered)
5. [Dashboard Process](#dashboard-process)
6. [Insights and Analysis](#insights-and-analysis)
7. [Conclusions and Recommendations](#conclusions-and-recommendations)

---

## Project Overview

This Power BI project explores a dynamic movie dataset sourced from KSR. The interactive dashboard was built to uncover trends in user ratings, genre popularity, and user demographics. It features a variety of visual elements including slicers, cards, gauges, and line charts that make the analysis both intuitive and impactful.

---

## Dataset Information

The dataset includes:
- Movie titles, genres, and release dates  
- User ratings across various movies  
- User demographic data including gender and occupation  

---

## Project Objectives

The main objective of this dashboard is to:
- Analyze rating patterns across decades, genres, and user demographics  
- Provide visual insights into movie popularity and audience preferences  
- Enable stakeholders to filter and drill into specific user or movie segments  
- Identify how rating behavior varies by gender and occupation over time  

---

## Key Questions Answered

1. **How many movies, genres, and users are in the dataset?**  
   - Cards display totals at a glance for quick reference.

2. **How do average ratings evolve over time and vary by gender?**  
   - A line chart illustrates trends in average ratings over the years, split by gender.

3. **Which movies performed above or below the average rating?**  
   - A gauge helps visualize how movies compare to the average rating threshold.

4. **How are users distributed by gender and occupation?**  
   - A column chart and slicers allow exploration of demographic makeup.

5. **How do different genres perform over time and across demographics?**  
   - Slicers by genre, decade, gender, and occupation enable segmented analysis.

---

## Dashboard Process

- **Data Loading and Preparation**  
  The dataset was imported into Power BI and cleaned using Power Query. Missing values were handled and key columns like dates, genres, and ratings were standardized.

- **DAX Measures and Calculations**  
  Custom DAX measures were created to compute total counts, averages, and segment-level insights such as average ratings per gender and decade.

- **Visual Design and Layout**  
  The dashboard features interactive cards, slicers, gauges, and line/column charts arranged to provide a seamless user experience. Slicers allow filtering across the entire report.

- **Testing and Optimization**  
  Final testing ensured smooth filtering, accurate metric calculations, and an intuitive layout optimized for both desktop and web viewing.

---

## Dashboard

![dashboard](assets/movie-dashboard.png)



---

## Insights and Analysis

The dashboard reveals key insights into how different user groups rate movies, which genres dominate each decade, and how user demographics interact with movie preferences. It highlights audience engagement trends and identifies high-performing movies by rating benchmarks.

---

## Conclusions and Recommendations

### Conclusions:
The analysis shows clear rating trends by gender, strong genre-specific performance, and valuable user engagement data. User occupation and gender noticeably influence movie preferences and rating behavior.

### Recommendations:
- Focus future releases and marketing strategies on genres with high average ratings.  
- Develop targeted campaigns based on occupation and gender insights.  
- Promote highly-rated movies that exceed the average rating threshold.  
- Use decade filters to tailor content recommendations based on generational preferences.
