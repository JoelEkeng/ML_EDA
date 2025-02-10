# Machine Learning Courses

---
## 🎯 Owner
- Ekeng Joel Effiong
- 10211100294
- Academic City University

## Advanced Data Analysis and GitHub Workflow

### Project Overview
This project focuses on deep data cleaning, exploratory data analysis (EDA), advanced data visualization, and feature engineering while incorporating best practices in GitHub collaboration. Students will analyze a dataset related to Gen-Z dating app usage, answer critical analytical questions, and document their workflow using GitHub.

---
## 📌 Hour 1: Deep Data Cleaning & GitHub Workflow
### **Task 1: Data Quality Assessment** (30 mins)
**Objective:** Ensure the dataset is clean and structured properly.

#### **Questions for Analysis:**
- Are there any duplicate rows? If yes, why might duplicates exist?
- Are there inconsistencies in categorical values (e.g., spelling variations, case sensitivity)?
- What should we do if a column has too many missing values?
- Are there outliers in numerical columns? Should we remove or adjust them?

#### **Activities:**
- Identify and handle missing values (drop, fill, or flag them).
- Detect and remove duplicate rows.
- Standardize categorical values (e.g., ensuring "Male" and "male" are the same).
- Detect and handle outliers using box plots and the IQR method.

#### **GitHub Integration:**
- Commit the cleaned dataset as **Version 1** with a commit message:
  > "Cleaned dataset: removed duplicates, handled missing values, and standardized categories."

### **Task 2: Dataset Documentation & Collaboration** (30 mins)
**Objective:** Improve dataset readability for team collaboration.

#### **Questions for Analysis:**
- If you were a new data scientist, what would you need to understand this dataset?
- How do you write effective column descriptions?
- What’s the best way to track dataset changes over time?

#### **Activities:**
- Write a **README.md** file explaining the dataset.
- Create a **data dictionary** (column names, types, and descriptions).
- Document all cleaning steps taken so far.

#### **GitHub Integration:**
- Push the **README.md** file and commit changes:
  > "Added README and data dictionary for dataset clarity."

---
## 📌 Hour 2: Deep Exploratory Data Analysis (EDA) & GitHub Branching
### **Task 3: Relationship Analysis** (30 mins)
**Objective:** Analyze relationships between variables.

#### **Questions for Analysis:**
- Does gender influence dating app preferences?
- Are people using multiple dating apps simultaneously?
- Which age group is most active on dating apps?
- Do urban vs. rural users show different usage patterns?

#### **Activities:**
- **Correlation Matrix & Heatmap:** Identify relationships between numerical variables.
- **Pivot Tables & Groupby Aggregations:** Summarize data by gender, age, and location.
- **Stacked Bar Charts:** Visualize categorical comparisons (e.g., dating app usage by gender).

#### **GitHub Integration:**
- Create a new branch **(feature-EDA)** and push exploratory work separately.
- Open a **Pull Request (PR)** for feedback.
- Discuss the importance of branching in collaborative ML projects.

### **Task 4: Detecting Patterns & Bias in Data** (30 mins)
**Objective:** Identify potential biases or unexpected trends in the dataset.

#### **Questions for Analysis:**
- Is there gender bias in dating app usage?
- Are certain demographics overrepresented?
- Is there a missing group of users that should be included?
- Can we trust this dataset for making general claims about Gen-Z dating in India?

#### **Activities:**
- Use **histograms and density plots** to compare distributions across demographic groups.
- Identify **overrepresented and underrepresented** groups.
- Discuss **ethical considerations** in data collection.

#### **GitHub Integration:**
- Update the PR with a commit message:
  > "Added bias detection analysis and demographic trends."

---
## 📌 Hour 3: Advanced Data Visualization & Feature Engineering
### **Task 5: Temporal & Regional Trends** (30 mins)
**Objective:** Analyze dating app usage over time and location.

#### **Questions for Analysis:**
- Are younger or older Gen-Z users more active?
- Does dating app preference change over time?
- Do metro city users behave differently from smaller towns?

#### **Activities:**
- **Line Charts:** Track trends over time.
- **Geospatial Visualizations:** Show differences in app usage across regions.
- **Bubble Charts:** Represent app popularity across age groups.

#### **GitHub Integration:**
- Merge the **feature-EDA** branch into **main**.
- Encourage **peer reviews** before merging.

### **Task 6: Feature Engineering for Future Modeling** (30 mins)
**Objective:** Prepare data for potential machine learning models.

#### **Questions for Analysis:**
- How can we convert categorical variables into numbers?
- Should we normalize numerical data? Why or why not?
- What new features could enhance predictive modeling?

#### **Activities:**
- Encode categorical variables using **One-Hot Encoding** or **Label Encoding**.
- Normalize numerical variables using **MinMaxScaler** or **StandardScaler**.
- Create a new feature, **"active app count"**, by summing the number of apps used per user.

#### **GitHub Integration:**
- Commit the engineered dataset:
  > "Feature engineering: Encoded categorical variables & added new features."

---
## 📌 Hour 4: Reflection, Documentation & GitHub Best Practices
### **Task 7: Collaborative Review & Documentation** (30 mins)
**Objective:** Strengthen teamwork and documentation skills.

#### **Questions for Analysis:**
- What were the most surprising insights from this dataset?
- What would you do differently with more time?
- How can we improve dataset documentation?

#### **Activities:**
- Write a **final summary** in the README.md file.
- Discuss findings in small groups.
- Review and merge all **Pull Requests (PRs)**.

### **Task 8: The Final Challenge (Interactive Q&A)** (30 mins)
**Challenge:** Answer questions based on the dataset & visualizations (no coding required).

#### **Final Questions:**
1. If a dating app wanted to expand into rural India, which insights would be most valuable?
2. If you were designing a new dating app based on this data, what two features would you add?
3. What were the biggest data cleaning challenges in this dataset?

#### **Final Outcomes:**
By the end of this session, students will have:
- Cleaned, explored, and visualized real-world data.
- Mastered **GitHub collaboration**.
- Developed insights into **Gen-Z dating app trends**.

---
## 🚀 How to Use This Repository
1. Clone this repository:
   ```bash
   git clone https://github.com/JoelEkeng/ML_EDA.git
   ```
2. Navigate to the project folder:
   ```bash
   cd your-repo
   ```
3. Create a new branch for your work: Task 3: Relationship Analysis can be found in this branch 
   ```bash
   git checkout -b feature-EDA
   ```
4. Push changes to GitHub:
   ```bash
   git add .
   git commit -m "Completed EDA analysis"
   git push origin feature-EDA
   ```
5. Open a **Pull Request** and request feedback.
