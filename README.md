<h1> Hotel Booking Cancellation Prediction </h1>

## 1. Project Overview
This project analyzes hotel booking data to build a classification model that predicts the likelihood of a booking being canceled. The goal is to help the Reservations & Revenue Management team proactively manage cancellation risk reducing vacant rooms and optimizing occupancy via timely actions (follow‑ups, incentives, or calibrated overbooking).

**Core Problem:**  
The hotel experiences a high volume of booking cancellations, with roughly 37% of confirmed bookings cancelled in the past year.
How can the hotel predict the likelihood of a booking being canceled early enough to:  
- Optimize overbooking limits using cost-based calculations.  
- Trigger proactive guest communication and upsell campaigns.  
- Prepare fair compensation packages in advance to mitigate reputational risk.  
- Secure overflow agreements with neighboring hotels for high-demand nights.

Key Objectives

Analyze customer and booking patterns related to cancellations.

Build and evaluate a prediction model that outputs per‑booking cancellation probability.

Translate model outputs into operational actions for the business.


We will evaluate the model using both **business metrics** and **machine learning metrics**.

**Business Metrics:**
- **Reduction in Revenue Loss** – Achieve a measurable and meaningful decrease in lost revenue from unsold rooms due to last-minute cancellations.
- **Occupancy Rate Improvement** – Increase in average occupancy by reselling predicted-to-cancel rooms.
- **Operational Efficiency** – Better alignment of staffing and room allocation with actual occupancy.
- **Guest Experience Impact** – Maintain or improve guest satisfaction by minimizing unnecessary walks.

**Machine Learning Metrics:**
- **Recall (Positive Class – Cancellations)** – Primary focus; measures the proportion of actual cancellations correctly identified. Target ≥ 80%.
- **F1-score** – Balances recall and precision; target ≥ 75% to ensure operational feasibility.
- **Precision** – Measures the proportion of predicted cancellations that actually cancel; monitored to control guest walk risk.
- **ROC-AUC & PR-AUC** – Assess the model’s ranking ability and performance under class imbalance.
- **Confusion Matrix** – Provides detailed counts of true positives, false positives, false negatives, and true negatives to support business cost analysis.

**Success Criteria:**
- Business: Achieve a meaningful and measurable reduction in cancellation-related revenue losses, improve occupancy, and increase operational efficiency.
- Machine Learning: Recall ≥ 80% and F1-score ≥ 75% on unseen data.

## 2. Data Sources
- Hotel Booking Demand Dataset — Booking records with customer/booking attributes and a binary label is_canceled. - This dataset contains booking information for a hotel located in Portugal, including customer demographics, booking behaviors, and whether the reservation was canceled. All personally identifying information has been removed.


## 3. Technologies Used
- Programming: Python (Pandas, NumPy, scikit‑learn, XGBoost, LightGBM)

- Visualization: Matplotlib, Seaborn, SHAP

- Environment: Jupyter Notebook

- Version Control: Git & GitHub

- Model Artifact: Pickle for saving the final trained pipeline

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. 
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.


```

## 5. Summary of Finding
### 5.1 Business Insight
In this section, you can present the **actionable insights** derived from the analysis results.
### 5.2 Actionable Recommendation
In this section, you can offer **actionable business recommendations** to address the identified problems.

## 6. Contact
- Name: Alief Dharmawan
- Email: aliefrnd@gmail.com
- Linkedin: https://www.linkedin.com/feed/
