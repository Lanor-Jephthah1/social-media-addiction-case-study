# social-media-addiction-case-study
# Social Media Addiction Among Students – A Data-Driven Study

## Overview

This project is part of the DMS Data Analytics mid-course capstone. It investigates the effects of social media addiction on students' academic performance, sleep patterns, and emotional well-being using a real-world dataset of 705 students.

## Objectives

* Analyse social media usage trends among students
* Explore the relationship between usage, sleep, academic performance, and emotional health
* Identify demographic patterns in social media addiction
* Provide actionable recommendations for digital wellness

## Dataset

* **Source:** Kaggle
* **Rows:** 705
* **Key Columns:**

  * `avg_daily_usage_hours`
  * `sleep_hours_per_night`
  * `mental_health_score`
  * `addicted_score`
  * `gender`, `academic_level`, `most_used_platform`

## Tools & Technologies

* **Python (Pandas, Matplotlib, Seaborn)** for data cleaning and analysis
* **Power BI** for interactive dashboards and visual storytelling
* **Excel** for preliminary checks

## Data Processing Steps

1. Standardized column names using regular expressions
2. Checked for and removed duplicate records
3. Created new features:

   * `weekly_usage_hours` = avg daily hours × 7
   * `addiction_level` = categorized based on `addicted_score`
4. Calculated basic statistics and grouped insights by gender and academic level

## Visualizations & Insights

* **Weekly Usage Histogram**: Most students spend 30–45 hours per week online
* **Platform Analysis**: Instagram, TikTok, and Facebook dominate
* **Addiction vs Mental Health**: Strong correlation found (r > 0.9)
* **Sleep vs Usage**: Negative correlation; higher usage leads to less sleep

## Recommendations

* Encourage use of screen-time management apps
* Promote digital detox initiatives and mental health programs
* Educate students on the academic effects of excessive social media use

## Deliverables

* `Cleaned_SocialMediaAddiction.csv` (processed dataset)
* `SocialMediaAddiction.pptx` (presentation slides)
* `SocialMediaDashboard.pbix` (Power BI file)
* Summary report (PDF or Word)

## Conclusion

This project highlights the significant impact of social media addiction on student life and provides data-backed recommendations for healthier digital habits. Institutions can use these insights to build more effective digital wellness support systems.
