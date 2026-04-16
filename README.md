# Meta-Ad-Analysis
**Project Overview**
This project provides a comprehensive performance tracking report for advertising campaigns running on Facebook and Instagram. The dashboard enables marketing teams to monitor reach, engagement, and conversion metrics, helping them optimize budget allocation and identify the most effective ad formats and platforms.

**Purpose & Key Objectives**
The primary goal is to evaluate the effectiveness of advertising spend through a data-driven approach.
**Performance Tracking:** Measure core KPIs like CTR, Conversion Rate, and ROAS.
**Audience Insights:** Analyze engagement patterns across different demographics, including age, gender, and location.
**Strategic Optimization:** Identify high-performing ad types (Video, Stories, Carousel, Image) to drive better ROI.

**Tech Stack**
Power BI: For data modeling and interactive visualization.
Power Query: Used for data cleaning and creating derived fields like day_of_week and time_of_day.
DAX: For calculating complex measures such as Click-Through Rate (CTR) and Conversion Rate

**Data Source & Architecture**
The project uses a Star Schema model based on simulated Meta Ads performance data.
Fact Table: ad_events (captures impressions, clicks, shares, and purchases).
Dimension Tables: ads, campaigns, and users (provides metadata on targeting, budget, and demographics)

**Key Insights**
Funnel Efficiency: While top-of-funnel engagement (CTR 11.76%) is strong, the lower-funnel Purchase Rate (0.61%) indicates a need for landing page optimization.
Format Superiority: Video and Stories ads significantly outperform static images in both reach and conversion.

<img width="849" height="486" alt="image" src="https://github.com/user-attachments/assets/5102b989-0cbc-4ca5-aa1d-3f4ce810258e" />




