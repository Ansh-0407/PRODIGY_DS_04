# Social Media Sentiment Analysis for Multi-Entity Branding

## Project Overview
This project focuses on analyzing public sentiment across **32 unique entities**, ranging from major gaming titles like *League of Legends* and *Call of Duty* to tech giants like *Microsoft* and *Nvidia*. Using a dataset of over **74,000 tweets**, I performed data cleaning, feature engineering, and visualization to identify brand health and consumer emotional patterns.

The project combines **R (Tidyverse)** for deep statistical processing and **Tableau** for high-level executive dashboarding.

## Dataset Statistics
- **Total Records:** 74,682
- **Key Features:** Tweet ID, Entity, Sentiment, Tweet Content.
- **Sentiment Distribution:**
    - **Negative:** ~30.2%
    - **Positive:** ~27.9%
    - **Neutral:** ~24.5%
    - **Irrelevant:** ~17.4%
- **Top Entities Analyzed:** Microsoft, Madden NFL, Tom Clancy's Rainbow Six, League of Legends, and Call of Duty.

## Technology Stack
- **R Programming:**
    - `readr`: For high-performance data ingestion.
    - `dplyr` & `tidyr`: For data manipulation and schema cleaning.
    - `ggplot2`: For complex data visualizations (Distribution and Boxplots).
- **Tableau:**
    - Interactive Brand Sentiment Dashboard.
    - Cross-filtering for entity-specific drill-downs.

## Analysis Workflow

### 1. Data Preprocessing (R)
- Handled missing values in tweet content.
- Removed duplicate entries to prevent bias from "bot" activity or spam.
- Standardized entity names for accurate grouping.

### 2. Feature Engineering
- Calculated **Tweet Length** (character count) as a proxy for engagement depth.
- Performed statistical summaries to see if "Negative" feedback is typically longer than "Positive" feedback.

### 3. Visual Analysis
- **Overall Tone:** Bar charts to identify the dominant sentiment across the entire ecosystem.
- **Brand Health:** Stacked percentage bars to compare sentiment ratios regardless of total volume.
- **Engagement Variability:** Boxplots to analyze the spread of tweet lengths per sentiment category.

## Tableau Dashboard
The Tableau component of this project serves as a Business Intelligence tool. It allows users to:
- Filter sentiment by specific Brand/Entity.
- Visualize word density to see common themes in customer complaints or praise.
- Compare engagement hotspots using Heat Maps.

## Conclusion
The analysis reveals that while sentiment is relatively balanced across the platform, certain gaming entities face significantly higher negative engagement compared to corporate tech entities. The ability to filter this data interactively provides brands with immediate insight into where they need to improve customer satisfaction.
