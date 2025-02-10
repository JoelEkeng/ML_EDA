# Gen-Z Dating App Dataset Documentation

## Dataset Documentation & Collaboration

## Project Overview
The dataset is used in analyzing Gen-Z dating app usage trends. It includes demographic details, app preferences, and behavioral patterns. The data will be used for cleaning, exploratory analysis, and feature engineering to derive insights into dating behaviors.

## Understanding the Dataset
As a new data scientist joining this project, for me to understand the dataset requires:
1. **Familiarity with Column Names & Types** – Refer to the data dictionary below.
2. **Context of Data Collection** – Understanding how and when the data was collected.
3. **Common Data Issues** – Identifying missing values, duplicates, and inconsistencies.
4. **Tracking Dataset Changes** – Using GitHub for version control and collaboration.

## Data Dictionary
| Column Name               | Data Type  | Description |
|---------------------------|-----------|-------------|
| User_ID                   | Integer   | Unique identifier for each user. |
| Age                       | Integer   | Age of the user. |
| Gender                    | Category  | Gender of the user (e.g., Male, Female, Other). |
| Location                  | Category  | User’s city or region. |
| Education                 | Category  | User’s highest education level. |
| Occupation                | Category  | User’s job or professional status. |
| Primary_App               | Category  | Main dating app used by the user. |
| Secondary_Apps            | Category  | Other dating apps the user engages with. |
| Usage_Frequency           | Category  | How often the user accesses dating apps. |
| Daily_Usage_Time          | Category  | Approximate time spent on dating apps daily. |
| Reason_for_Using          | Category  | Main reason for using dating apps (e.g., relationships, friendships). |
| Satisfaction              | Integer   | User satisfaction level (on a scale of 1-10). |
| Challenges                | Category  | Issues users face when using dating apps. |
| Desired_Features          | Category  | Features users would like to see in dating apps. |
| Preferred_Communication   | Category  | How users prefer to communicate on apps. |
| Partner_Priorities        | Category  | Qualities users prioritize in a potential partner. |

## Writing Effective Column Descriptions
To write an effective column descriptions:
- **Be Clear and Concise** – Use simple and precise language.
- **Include Data Types** – Specify whether it's an integer, category, or other format.
- **Explain Purpose** – Describe what each column represents and its significance.
- **Provide Examples** – Where necessary, include sample values.

## Dataset Cleaning Steps
1. **Checked for missing values** – Used imputation or removed incomplete records.
2. **Handled duplicates** – Identified and removed duplicate entries.
3. **Standardized categorical values** – Ensured consistent formatting (e.g., "Male" and "male" standardized to "Male").
4. **Detected and handled outliers** – Used statistical techniques like IQR and Boxplot.
5. **Converted data types** – Ensured correct formats for analysis.

## Tracking Changes Over Time
The best way to track dataset changes is by using **GitHub version control**:
- **Initial Dataset Upload** – Commit raw dataset to GitHub.
- **Data Cleaning Commits** – Record changes with messages like "Handled missing values and removed duplicates."
- **Feature Engineering Updates** – Document transformations and new variables.
- **Branching for Analysis** – Create separate branches for exploratory analysis.
- **Final Versioning** – Maintain version numbers (e.g., `dataset_v1.csv`, `dataset_v2.csv`).

## GitHub Integration
To track dataset updates effectively:
```bash
# Clone the repository
git clone https://github.com/JoelEkeng/ML_EDA.git
cd your-repo

# Create a new branch for cleaning
git checkout -b data-cleaning

# Add cleaned dataset
git add dataset.csv

# Commit changes
git commit -m "Cleaned dataset: removed duplicates, handled missing values."

# Push to repository
git push origin data-cleaning
```

