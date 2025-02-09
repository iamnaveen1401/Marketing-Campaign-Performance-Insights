# Marketing Campaign Performance Insights

## Overview

## Project Title: Marketing Campaign Performance Insights
**Problem Statement:**
In the highly competitive landscape of digital marketing, effectively evaluating the success of
various marketing campaigns is essential for optimizing return on investment (ROI) and
improving overall performance. Despite having extensive data on multiple campaigns, there
is a need for a thorough analysis to assess and compare key metrics such as conversion
rates, acquisition costs, and ROI across different campaign types, channels, and audience
segments. This project aims to uncover actionable insights by examining temporal trends,
geographical influences, and audience responses to identify factors driving campaign
success and provide recommendations for enhancing future marketing strategies.

**Dataset Link:**
[Dataset-Link](https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/marketing_campaign.csv)


## Dataset

The dataset used in this project is stored in `marketing_campaign_data.csv` and contains the following key columns:

- **Campaign\_ID**: Unique identifier for each campaign.
- **Company**: Organization running the campaign.
- **Campaign\_Type**: Type of marketing effort (email, social media, influencer, etc.).
- **Target\_Audience**: Demographic segment targeted.
- **Duration**: Campaign duration in days.
- **Channels\_Used**: Platforms used (email, social media, YouTube, etc.).
- **Conversion\_Rate**: Percentage of leads that converted.
- **Acquisition\_Cost**: Cost per customer acquisition.
- **ROI**: Return on investment.
- **Location**: Geographical area of the campaign.
- **Language**: Language of the campaign content.
- **Clicks**: Total number of clicks received.
- **Impressions**: Total number of views.
- **Engagement\_Score**: Score from 1 to 10 representing audience engagement.
- **Customer\_Segment**: Specific customer group targeted.
- **Date**: Date when the campaign occurred.

## Project Steps

1. **Load the Dataset**

   - Read the `marketing_campaign_data.csv` file into a pandas DataFrame.

2. **Descriptive Analysis**

   - Display first few rows, dataset shape, and summary statistics.
   - Identify unique values in categorical columns.

3. **Exploratory Data Analysis (EDA) & Visualization**

   - **Campaign Performance:**
     - Scatter plot of Acquisition\_Cost vs. ROI.
     - Bar chart for average Conversion\_Rate by Channels\_Used and Campaign\_Type.
     - Box plot of Engagement\_Score across different Campaign\_Types.
     - Bar chart comparing average ROI by Company.
     - Heatmap for correlation between Engagement\_Score and Conversion\_Rate.
   - **Customer Segmentation:**
     - Count plot for Target\_Audience distribution.
     - Bar chart showing highest Conversion\_Rate per Language by Customer\_Segment.
     - Box plot for Acquisition\_Cost across Customer\_Segment categorized by Channels\_Used.
     - Bar chart for average Conversion\_Rate by Language.
   - **Channel Effectiveness:**
     - Bar chart for Engagement\_Score by Channels\_Used and Campaign\_Type.
     - Pie chart for total ROI distribution across Channels\_Used.
     - Scatter plot for Clicks vs. Impressions by Channels\_Used.

4. **Time-Based Analysis**

   - Histogram of campaign duration.
   - Line charts for Conversion\_Rate over time by Company and Engagement\_Score trend over time.

5. **Geographic Analysis**

   - Bar chart for highest Acquisition\_Cost by Location.
   - Bar chart for Conversion\_Rate by Location and Target\_Audience.
   - Pie chart illustrating ROI proportion by Location.

## Requirements

To run this project, install the following Python libraries:

```sh
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

## Usage

Run the Python script to execute the analysis:

```sh
[python marketing_analysis.py](https://colab.research.google.com/drive/1XV8NSsTzzferqAmz6oeQIlHKLDb-2HZO?usp=sharing)
```

## Results & Insights

This project helps marketers understand the effectiveness of different campaigns by providing:

- Performance comparisons of campaign types and channels.
- Insights into customer engagement and conversion.
- Data-driven recommendations for improving marketing strategies.

