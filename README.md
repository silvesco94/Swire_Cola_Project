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

##  [Business Value of Solution](Swire%20Coca-Cola%20Capstone%20(1).pptx).


The predictive maintenance solution developed for Swire Coca-Cola directly addresses the $60M annual loss caused by unexpected machine downtime. By leveraging survival analysis and machine learning models, this solution provides:

1. **Improved Maintenance Planning**:
   - Proactively identifies high-risk equipment likely to fail, enabling preemptive repairs.
   - Reduces unplanned failures, minimizing disruptions to production schedules.

2. **Enhanced Operational Efficiency**:
   - Maximizes output by keeping machines running reliably with minimal delays.
   - Supports scalable maintenance strategies adaptable to future production needs.

3. **Cost Savings**:
   - Reduces downtime-related costs by optimizing maintenance schedules.
   - Helps meet production deadlines, maintaining customer satisfaction and revenue targets.

With this solution, Swire Coca-Cola can achieve reliable, efficient, and scalable production processes, ensuring long-term business growth and operational stability.

## Difficulties that your group encountered along the way.

## Challenges and Difficulties Faced

During the analysis and modeling process, several challenges were encountered that significantly influenced the outcome of the project:

1. **High Percentage of Missing Equipment IDs**:
   - Over 80% of the equipment ID data was missing, which posed a significant obstacle to granular analysis at the equipment level.
   - This missing data restricted the model's ability to distinguish failure patterns or breakdown frequencies tied to specific machines, potentially impacting the model's precision.

2. **Imbalance in Breakdown Records**:
   - The distribution of breakdown counts was uneven, with some functional areas experiencing significantly higher breakdowns than others.
   - This imbalance could lead to the model overemphasizing high-frequency breakdown areas while underperforming for lower-frequency areas.

3. **Data Quality Issues in Date Columns**:
   - Inconsistencies in execution start and finish dates required extensive preprocessing, including handling missing values and reformatting dates.
   - These issues complicated the feature engineering process, particularly for time-based variables like repair durations and quarterly trends.

4. **Exploratory Analysis Observations**:
   - Certain functional areas consistently exhibited high breakdown counts, such as SUZUKA PRODUCTION, while others like COTA PRODUCTION were more stable.
   - Temporal trends revealed seasonal spikes and dips in breakdown counts, adding complexity to the feature engineering process as the model needed to capture these nuances.

These challenges highlight the importance of data quality and completeness in predictive modeling projects. Addressing these issues through rigorous preprocessing and thoughtful feature engineering was essential to derive actionable insights despite the limitations.

