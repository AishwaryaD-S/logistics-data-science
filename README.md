# Logistics Data Science Internship Project
**Domain:** Urban Last-Mile E-Commerce Delivery Optimization

---

## 1. Project Scenario & Overview
* **Scenario:** Addressing supply chain distribution network delays, rising fuel costs, and unpredictable urban traffic congestion through data-driven planning and machine learning.
* **Objective:** Build an end-to-end data science pipeline covering strategic planning, automated data cleaning, exploratory data analysis, and predictive machine learning modeling for urban last-mile logistics.

---

## 2. Dataset Simulation & Characteristics
To handle raw, unorganized telemetry logs, the project utilizes a programmatically simulated dataset reflecting real-world conditions:
* **Key Variables Tracked:** Order IDs, delivery distances (km), transit times (hours), fuel costs (USD), package weights (kg), vehicle types, and weather conditions.
* **Simulation Approach:** Generated dynamically using Python (`NumPy` and `Pandas`) to mimic live GPS tracking and fulfillment records without needing external file dependencies.

---

## 3. Comprehensive Task Breakdown

### Task 1: Strategic Planning and Framework Design
* **KPIs Defined:** On-Time Delivery Rate (OTDR >95%), Average Transit Time, and Cost per Kilometer (CPK).
* **Roadmap:** Outlined an end-to-end data science structure transitioning logistics operations from reactive models to proactive, data-driven intelligence.

### Task 2: Data Cleaning and Preprocessing Pipeline
* **Missing Value Imputation:** Addressed missing GPS and log entries using median imputation to protect against heavy distribution skewness.
* **Outlier & Constraint Handling:** Applied Interquartile Range (IQR) filtering to isolate anomalies and removed physical constraint violations (e.g., negative costs).
* **Normalization:** Performed Min-Max Feature Scaling to normalize variables between 0 and 1.

### Task 3: Advanced Exploratory Data Analysis (EDA) & Visualization
* **Statistical Insights:** Calculated central tendencies, variances, and grouped performance metrics across vehicle types and weather conditions.
* **Visualization Portfolio:** Generated correlation matrices (heatmaps), weather impact boxplots, and regression scatter plots to uncover cost drivers and transit bottlenecks.

### Task 4: Predictive Modeling and Logistics Optimization
* **Machine Learning Model:** Implemented and tuned a **Random Forest Regressor** using GridSearchCV and cross-validation to forecast precise delivery transit times.
* **Performance Metrics:** Validated using RMSE, MAE, and R-Squared ($R^2$) scores to ensure high generalization accuracy.
* **Optimization Strategies:** Proposed dynamic real-time rerouting, micro-hub inventory positioning, and adaptive workforce capacity planning based on model feature importances.

---

## 4. Repository Files & Structure
* **Task 1:** `Task 1.ipynb` & `Task 1.docx`
* **Task 2:** `Task 2.ipynb` & `Task 2.docx`
* **Task 3:** `Task 3.ipynb` & `Task 3.docx`
* **Task 4:** `Task 4.ipynb` & `Task 4.docx`
* **Dependencies:** `requirements.txt` (lists all required Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`)
