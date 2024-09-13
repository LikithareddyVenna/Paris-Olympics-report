
# Paris Olympics Performance Dashboard
## Introduction
This Power BI report provides an in-depth analysis of paris Olympics 2024 performance across different Countries, Athletes and Games. 
## Table Of Contents
1. Introduction
2. Report Overview
3. Data Sources
4. Description of Each CSV File
5. Report Structure
6. License
7. Acknowledgments 

## Report Overview
- **Report Name:** Paris Olympics Performance Dashboard
- **Report Author:** Likitha Reddy Venna
- **Date Created:** September 7,2024
- **Last Updated:** September 11,2024
- ** Description:** This Dashboard tracks the Athletes performance by Country and Sports.

## Data Sources
1. **Kaggle Dataset - Paris 2024 Olympic Summer Games**
    - **Type:** Multiple CSV Files
    - **Source:** https://www.kaggle.com
    - **Dataset Name:**  Paris 2024 Olympic Summer Games
    - ** Dataset URL:** https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games
    - **Uploader:** Petro

### Description of Each CSV File:
- **File 1: 'Athletes.CSV'**
  - **Content and Purpose:** Contains Athletes Demographic data used to analyze Athletes based on age, gender, country, sports.
  - **Key Columns:**
    - 'Disciplines' - Sports played by the Athletes.
    - 'Country' - For which Country Athletes playing.
    - 'Age' - The age of individual athelte calculated as the difference between the current date and the individual's date of birth.
    - 'Age Category' - Categorizes individuals based on their age. The categories are Under 15, 16-20, 21-25, 26-30, 31-35, 36-40, 41-45, 46-50, 51+.
    - ** Data Quality Checks:**  Filtered for duplicates and verified data consistency.

- **File 2: 'Medalists.CSV'**
   - **Content and Purpose:** Contains Medalists Demographic data used to analyze Medalists based on gender, country, discipline, name.
   - **Key Columns:**
    - 'Disciplines' - Sports played by the Athletes.
    - 'Country' - For which Country Athletes playing.
    - 'gender' - Gender of the athlete.
    - 'name' - Name of the athelte.
    - ** Data Quality Checks:**  Filtered for duplicates and verified data consistency.
- **File 3: 'Medals_total.CSV'**
   - **Content and Purpose:**  Contains Athletes Demographic data used to analyze Athletes based on medals they won.
     - **Key Columns:** 
      - Gold Medal- Athletes who won Gold Medal.
      - Silver Medal- Athletes who won Silver Medal.
      - Bronze Medal - Athletes who won Bronze Medal.
    - ** Data Quality Checks:**  Filtered for duplicates and verified data consistency.

## Report Structure
- **Page 1 - Overview:** High Level summary of Athletes Performance.
- **Page 2 - Athletes:** Detailed view of Athletes Performance by gender, age and different medals.
- **Page 3 - Country:** Insights into Athletes performance by Country.

## License
This report is licensed under MIT License.

## Acknowledgments
Special thanks to the Petro for their support in providing Dataset.


