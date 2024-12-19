# Predictive Fundraising Analysis for a Charity Foundation

This project is focused on applying **statistical inference** and **supervised learning** techniques using R to optimize a charity foundation’s fundraising campaign for 2024. The goal is to determine the optimal number of appreciation kits to send to members to maximize donations while considering budget constraints.

---

## 📊 **Project Overview**

### Objective:
- Develop a predictive model to identify which members should receive an appreciation kit to maximize donation profits.
- Evaluate the impact of sending kits on donation behavior.
- Submit a report summarizing the methodology and results and participate in a leaderboard-based competition.

---

## 📋 **Dataset Details**

The project involves multiple data sources provided in CSV format:

1. **`MembersList.csv`**:  
   Contains basic member information updated at the end of 2023. Each member has a unique identifier.

2. **`DonationHistory.csv`**:  
   A list of all donations received until 2023. Each member can donate once per year.

3. **`NewsLetterRead.csv`**:  
   Data on whether members opened newsletters sent by the foundation in 2023.

4. **`SocialNetworkUsage.csv`**:  
   Data on social media activity, linking certain social media users to their membership IDs.

---

## 🧠 **Project Phases**

### **Phase 1: Predictive Modeling and Report**

- **Defining Target and Predictors:**
  - Choose the target variable and predictors to model donation behavior effectively.
  - Justify the choice of variables based on their relevance and predictive power.

- **Exploratory Data Analysis (EDA):**
  - Analyze the distribution and relationships between the chosen variables.
  - Handle missing values, if any, and transform data as needed.

- **Model Development:**
  - Use supervised learning techniques to predict donations.
  - Train and evaluate the model using appropriate methodologies such as cross-validation.

- **Optimization:**
  - Determine the number and identity of members to receive kits based on model predictions.
  - Ensure the solution maximizes net profits (donations minus kit costs).

- **Deliverables:**
  - Submit a report in **PDF format** created using **R Markdown** or **Quarto**, including:
    1. Details of the predictive model and methodology.
    2. Analysis of model performance.
    3. Recommendations on kit distribution.

---

### **Phase 2: Competition**

- Submit a CSV file with the IDs of members selected to receive kits to the competition platform.
- The platform evaluates each team’s profit (donations minus costs) in two stages:
  - **Interim Leaderboard:** Reflects the results during the competition based on partial data.
  - **Real-Life Leaderboard:** Evaluates the final model on a hidden test dataset to determine actual performance.

- **Evaluation Criteria:**
  - Profit must exceed the baseline (no kits sent) for a passing score.
  - Scores are calculated based on relative performance to the top 10% of teams.

---

## 🚀 **Technologies Used**

- **R Programming Language**:
  - **R Markdown/Quarto** for report generation.
  - Libraries for data analysis, visualization, and model building:
    - `tidyverse`, `caret`, `glmnet`, and `xgboost`.

- **CSV Data Handling**:
  - Load, clean, and preprocess multiple CSV files into a unified dataset.

- **Supervised Learning**:
  - Use regression and classification models to predict donation likelihood and amounts.

- **Optimization**:
  - Apply cost-benefit analysis to identify the optimal kit distribution strategy.

---

## 🛠 **Key Challenges**

1. Defining an effective target variable and predictors for the problem.
2. Balancing the trade-off between kit costs and increased donation potential.
3. Validating model robustness on hidden test data for the competition leaderboard.

---

## 📈 **Expected Outcomes**

- A clear and actionable strategy for kit distribution to maximize donation profits.
- Insights into member behavior based on the predictive model.
- A final ranking on the competition’s real-life leaderboard, demonstrating the efficacy of the solution.

---

This project demonstrates the application of statistical modeling, machine learning, and business optimization techniques to solve a real-world fundraising problem.
