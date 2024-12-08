# Swire_Cola_Project
Predictive maintenance for Swire Coca-Cola


## Business Problem  

### [Business Problem Statement](Business%20Problem%20Statement.docx)

Swire Coca-Cola's production plants operate six facilities that produce approximately 192 million cases of beverages annually. However, the plants experience a production shortfall, producing only 94.4% of the total intended cases due to unplanned mechanical breakdowns and maintenance issues. This gap, costing the company approximately $60 million in lost productivity annually, results from unanticipated downtimes caused by machinery failures across various production lines. The current process relies on reactive maintenance through an Internal Warehouse Controller (IWC) system, which issues work orders only after machinery failures occur, leading to significant delays in repairs and downtime.

### Deliverables
- A validated predictive model.
- Insights into machine failure patterns.
- A final report detailing findings and recommendations.


## [Group Modeling Assignment](Group%20Modeling%20Assignment.html)

OOur group developed a comprehensive predictive maintenance solution for Swire Coca-Cola to address unplanned downtimes and improve production efficiency. Leveraging advanced analytics techniques, we implemented the following models:

1. **Survival Analysis (Main Focus)**:
   - Applied survival analysis to estimate the likelihood of machinery failures over time.
   - Provided actionable insights into expected failure timelines, allowing maintenance teams to proactively schedule repairs before breakdowns occurred.
   - Enabled better resource allocation and minimized unexpected production disruptions.

2. **Random Forest Model**:
   - Used a Random Forest algorithm to identify and rank the key factors driving machine breakdowns, such as component wear, machine age, and environmental conditions.
   - Highlighted critical variables to guide targeted maintenance interventions and resource prioritization.

3. **Logistic Regression**:
   - Built a logistic regression model to predict the probability of equipment failures under specific operating conditions.
   - Delivered a straightforward and interpretable model for decision-makers, offering additional layers of insight for maintenance planning.

These approaches worked synergistically to empower Swire Coca-Cola with data-driven strategies to anticipate equipment failures, reduce downtime, optimize maintenance schedules, and enhance overall production efficiency. The solution is projected to significantly reduce operational costs and improve productivity by addressing the root causes of unplanned downtimes.


## [My Personal Contribution](modeling%20assignment.Rmd)

In this project, I developed a **Random Forest-based predictive maintenance model** to assist Swire Coca-Cola in minimizing equipment downtime. My contributions focused on key aspects of data preprocessing, feature engineering, visualization, and model evaluation:

1. **Data Cleaning and Preprocessing**:
   - Transformed and cleaned historical maintenance data, including date conversions and handling missing values.
   - Aggregated breakdown counts and maintenance records by year and quarter to provide structured temporal insights.

2. **Feature Engineering**:
   - Created lagged features, moving averages, and cumulative breakdown totals to capture recent and historical trends.
   - Engineered interaction terms and polynomial features to improve predictive power.

3. **Exploratory Analysis and Visualizations**:
   - Developed visualizations to uncover quarterly breakdown patterns, repair durations, and trends across functional areas.
   - Created heatmaps and line plots to highlight critical insights for operational planning.

4. **Model Development and Evaluation**:
   - Trained and optimized a Random Forest regression model, achieving high predictive accuracy with 98% of variance explained.
   - Conducted thorough performance evaluations using metrics like MAE, RMSE, and R², interpreting their implications for business operations.
   - Analyzed feature importance to identify key drivers of breakdowns, guiding maintenance prioritization.

5. **Advanced Modeling**:
   - Experimented with advanced feature transformations, including log-transformed targets and interaction terms, to enhance the model's robustness.

These contributions ensured a data-driven approach to predictive maintenance, enabling Swire Coca-Cola to proactively address equipment failures, reduce costs, and improve production efficiency.




