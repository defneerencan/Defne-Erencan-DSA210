# Defne Erencan DSA210 Term Project

## Introduction
This project aims to analyze my **seasonal spending habits** using my **Akbank card transaction history**. The goal is to compare how my financial behavior differs between **summer vacation** and the **school term**, focusing on spending trends, social activities, and personal expenses. Additionally, I will examine how my spending changes when I return to my **family home**, where my expenses are generally lower.

## Motivation
As a university student, my daily routine and financial priorities change significantly depending on the time of the year. Some key differences I want to explore include:
- **Higher expenses during school periods** due to academic needs and transportation.
- **Increased social spending in summer** as I have more free time.
- **Personal spending variations**, such as investing in self-care or relaxation during summer versus necessities during school.
- **How my study workload impacts discretionary spending**, including food, coffee, and leisure activities.
- **Lower spending when at my family home**, as many expenses (food, utilities, etc.) are covered by my family.

## Data Source
The dataset consists of **Akbank card transaction records**, exported as an **Excel file**. The key columns include:
- **Date & Time** – When the transaction occurred.
- **Transaction Amount** – The amount spent per transaction.
- **Category** – The type of purchase (food, transportation, entertainment, etc.).
- **Merchant Name** – Where the transaction took place.
- **Remaining Balance** – Card balance after each transaction.

## Hypothesis
- **Spending Patterns:** I expect my **total spending** to be **higher during school periods** due to daily necessities and transportation costs.
- **Social Activities:** I assume my **social spending increases in summer**, with more outings and restaurant visits.
- **Self-Care vs. Academic Expenses:** My spending on **self-care (books, skincare, hobbies)** might increase in summer, whereas during school, I focus on **study-related costs**.
- **Coffee Consumption:** I predict a **higher number of coffee purchases** during the academic term due to exam stress and study sessions.
- **Lower Spending at Family Home:** I assume my expenses significantly drop when I return home, as I don’t have to pay for food, utilities, and other necessities.

## Tools & Technologies
- **Python**
  - `pandas` – Data structuring and manipulation
  - `matplotlib` & `seaborn` – Data visualization
  - `numpy` – Mathematical calculations
  - `scipy.stats` – Statistical analysis
- **Jupyter Notebook** – Data analysis and visualization
- **Excel** – Data collection and initial categorization

## Data Processing
- **Cleaning Data:** Removing unnecessary columns (e.g., receipt numbers).
- **Categorizing Transactions:** Assigning purchases into:
  - **Essential spending** (food, transportation, school supplies)
  - **Discretionary spending** (entertainment, self-care, shopping)
  - **Social spending** (restaurants, outings, events)
- **Dividing into Time Periods:**
  - **Summer Vacation (June – September)**
  - **School Term (October – May)**
  - **Family Home Periods (Winter & Summer Breaks)**

## Data Analysis
- **Total Spending Over Time:** Comparing overall spending in summer vs. school periods using **line charts**.
- **Category-Based Analysis:** Visualizing how much I spend on different categories using **bar charts and other visualization methods**.
- **Social vs. Academic Spending:** Examining changes in **social spending vs. study-related purchases**.
- **Coffee Consumption Trends:** Analyzing the **frequency and cost of coffee purchases** during exam weeks.
- **Balance Management:** Observing how quickly my card balance depletes during school vs. summer.
- **Family Home Spending Trends:** Comparing spending patterns during breaks when I am at home versus when I am at university.

## Hypothesis Testing
- **Spending Variance Test:**
  - Null Hypothesis (H₀): There is **no significant difference** in spending between school and summer periods.
  - Alternative Hypothesis (H₁): **Spending is significantly different** between these periods.
  - Conducting **t-tests** to determine statistical significance.

- **Coffee Consumption Test:**
  - Null Hypothesis (H₀): Exam weeks do **not** impact coffee purchases.
  - Alternative Hypothesis (H₁): **Exam weeks correlate with increased coffee spending**.

- **Family Home Spending Test:**
  - Null Hypothesis (H₀): Spending is **the same** when I am at university versus when I am at my family home.
  - Alternative Hypothesis (H₁): Spending **significantly decreases** when I return home.

## Findings
- **School term spending is generally higher**, with more frequent small purchases.
- **Social spending is dominant in summer**, with more expenses in restaurants and cafes.
- **Coffee purchases increase during exam periods**, supporting the assumption that study workload affects spending behavior.
- **Self-care and personal expenses rise in summer**, while academic expenses dominate school months.
- **Balance depletion is faster in school months** due to frequent food and transportation costs.
- **Spending significantly drops when I am at my family home**, as I don’t need to pay for meals, utilities, and transportation.

## Limitations & Future Work
- **Personalized data:** The analysis is based on my own spending behavior, so it is not generalizable.
- **Limited Data Range:** Expanding the dataset to multiple years could improve trend detection.
- **Automating Categorization:** A machine learning model could be used for automatic categorization of expenses.
- **Future Visualization Improvements:** Creating an interactive dashboard to track spending habits in real-time.

---
This project follows the **DSA210 Project Guidelines** and provides a data-driven approach to understanding how my spending habits change throughout different seasons of the year.

