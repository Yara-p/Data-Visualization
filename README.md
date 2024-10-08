# US Labor Force Suicide Tableau Dashboard

## Overview
This project offers an interactive data visualization of **Labor Force Suicide in the United States**, focusing on individuals aged 15-65. The dataset, sourced from the [CDC](https://www.cdc.gov/suicide/facts/data.html), allows users to explore both geographical and demographic disparities in suicide rates. The dashboard is hosted on [Yara's Tableau Public](https://public.tableau.com/views/USSuicideVisualizationWorkbook/GeographicalAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), and the [Complete File](https://github.com/Yara-p/Data-Visualization/blob/main/US%20Suicide%20Tableau%20Dashboard.twbx) is available in this GitHub repository.


## Data Preparation Using Python
In addition to using Tableau for visualization, I utilized Python to automate the data preparation process. This automation includes:

1. **File Renaming**: A Python script was used to rename and organize multiple CSV files by adding prefixes based on age groups, making it easier to distinguish and analyze different demographic categories.
2. **Data Cleaning**: The script also automates the removal of redundant metadata within the CSV files, ensuring cleaner datasets for visualization and analysis.

The automation scripts streamline data preparation, making it more efficient to handle large datasets and maintain consistency across files.

## What Users Can Do With The Dashboard:

1. **Geographical Disparity Analysis**:
   - **Explore Suicide Rates by State**: Compare suicide rates across all US states and adjust the threshold to visualize the severity of suicide disparities across the country.
   - **Track Temporal Changes**: Rank states by the number of suicide deaths and analyze trends over time. This allows you to identify which states have experienced the most significant changes in suicide rates.
   - **Interactive Exploration**: Use filters to drill down into specific regions and time periods for a more focused analysis of high-risk areas.

2. **Demographic Disparity Analysis**:
   - **Understand Age Group Differences**: Discover which age groups are most affected by suicide, with clear trends for those aged 26-35 and 46-55.
   - **Analyze Gender and Racial Disparities**: View the stark differences between male and female suicide rates, as well as notable racial disparities, particularly among White and Native American populations.
   - **Examine Suicide Methods**: Compare methods of suicide (e.g., firearms, suffocation, poisoning) across different demographics to understand which methods are most prevalent in each group.
   - **Investigate Seasonality Trends**: Although no strong seasonal trends are evident, you can explore whether suicide rates fluctuate across different times of the year.


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Yara-p/Data-Visualization.git

