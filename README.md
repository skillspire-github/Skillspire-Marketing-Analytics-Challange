# Skillspire-Marketing-Analytics-Challange
Welcome to the Skillspire Marketing Analytics Challenge, a hands-on data project designed to test your skills in data analysis, visualization, and statistical modeling using Python.

You’ll step into the role of a Marketing Data Analyst at RetailNova, a fast-growing e-commerce company. Your mission:

Unlock insights into customer behavior, evaluate marketing campaign performance, and identify what drives sales and churn.

This challenge is perfect for:

Data analysts, students, and career switchers building portfolio projects

Participants in data hackathons or analytics bootcamps

Anyone eager to practice real-world marketing data problems with Python

📂 Dataset

The dataset retailnova_marketing.csv contains 10,000 synthetic customer records, simulating real-world marketing data.

Columns Overview
Variable	Description
customer_id	Unique customer identifier
age	Customer age (18–70)
gender	Male / Female / Other
region	North, South, East, West
acquisition_channel	How the customer was acquired (Social Media, Search Ads, Referral, Email, Organic)
signup_date	Date of account creation
last_purchase_date	Date of most recent purchase
total_purchases	Number of purchases in past 12 months
avg_order_value	Average order value (USD)
campaign_exposure	Whether the customer saw the recent ad campaign (Yes/No)
campaign_clicks	Number of ad clicks
time_on_site	Average time spent on website (minutes/session)
churned	1 if the customer hasn’t purchased in 6 months
revenue_last_12m	Total revenue from customer in past 12 months
🎯 Challenge Tasks
Part 1 — Descriptive Statistics (30 pts)

Summarize demographics and customer behavior

Identify top-performing acquisition channels

Compare engagement between churned vs active users

Part 2 — Data Visualization (30 pts)

Use matplotlib, seaborn, or plotly to visualize:

Age and purchase frequency distributions

Sales and campaign trends

Churn by region or acquisition channel

💡 Bonus: Build an interactive dashboard (Plotly or Streamlit)

Part 3 — Statistical Modelling (40 pts)

Hypothesis testing: Does campaign exposure affect purchases?

Regression/classification model to predict churn probability

Identify key predictors and interpret results

🧮 Scoring Rubric
Category	Description	Points
Data Exploration	Cleaning, descriptive analysis	20
Visualization & Storytelling	Quality, clarity, interpretability	30
Modeling & Analysis	Model accuracy, explanation	30
Insight & Business Impact	Actionable takeaways	15
Creativity / Bonus	Innovation in approach	5
📘 Deliverables

Submit a Jupyter Notebook (.ipynb) containing:

Clean, documented Python code

At least 3 data visualizations

Statistical results & interpretations

Final business insights

Optional: Include an HTML or PDF export of your notebook.

💡 Tips for Participants

Tell a data story — make results understandable for business audiences.

Focus on why the insights matter to marketing decisions.

Use visual storytelling and markdown formatting in your notebook.

Think like a data-driven strategist, not just a coder.

🏆 Example Insights

• Customers acquired via Social Media show higher engagement but lower retention.
• Campaign exposure increases total purchases by ~12% (p < 0.05).
• Logistic regression reveals time_on_site and total_purchases as top predictors of churn.

⚙️ Technologies

Python 3.x

pandas, numpy

matplotlib, seaborn, plotly

scikit-learn, statsmodels
