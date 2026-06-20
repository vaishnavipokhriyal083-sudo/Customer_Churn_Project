# Customer_Churn_Project
Retaining existing customers is far more cost-effective than acquiring new ones. This data science project builds a robust predictive pipeline to identify high-risk customer accounts likely to terminate their subscriptions. By analyzing critical behavioral patterns. such as contract structures, tenure lengths, and billing profiles.this project empowers businesses to execute proactive, data-driven retention marketing strategies before churn occurs.

**🛠️ Machine Learning Workflow**
The project implements a complete, end-to-end data science lifecycle inside Colab Notebook environment:
Exploratory Data Analysis & Preprocessing: Cleaning raw data, handling missing values, and applying feature transformations like Label Encoding to prepare categorical business metrics for modeling.
Supervised Classification: Building, tuning, and comparing multiple algorithmic baselines to isolate the most reliable predictive boundaries.
Diagnostic Evaluation: Moving beyond basic accuracy to analyze precision mechanics and matrix layouts, ensuring business interventions are highly targeted and cost-effective.

**📊 Model Performance Summary**
Three distinct classification frameworks were trained and cross-evaluated on the testing dataset. Logistic Regression emerged as the optimal engine, proving that primary churn drivers share a strong, direct linear relationship with human behavior:
Logistic Regression (Winner): 82.27% Accuracy — Delivers clean, top-tier generalization bounds across linear boundaries.
Random Forest Classifier: 0.89% Accuracy —  Established a reliable initial structural baseline for project data.
Decision Tree Classifier: 76.59% Accuracy — A highly robust ensemble method that effectively aggregates collective decision tree votes.

**📈 Strategic Business Insights**
Targeted Efficiency: The final predictive framework achieved a Precision Score of 79.16%. This confirms that out of all accounts flagged as high-risk, approximately 4 out of 5 are genuine churn targets. This safeguards corporate retention budgets against wasteful spending on satisfied users.
Confusion Matrix Validation: Deep matrix mapping successfully isolated 92 true negatives and 19 true positives, showcasing a balanced grasp of customer stability trends.

**💻 Tech Stack**
_Language:_ Python
_Libraries:_ Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
