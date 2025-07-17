Fitness Activity Analysis

A comprehensive exploratory and predictive analysis pipeline on user-generated fitness tracker telemetry data. This project leverages Python-based data manipulation, visualization, and statistical methods to uncover latent patterns in activity behavior, caloric expenditure, BMI distribution, and temporal usage trends.

Project Overview

The dataset comprises multi-table daily logs capturing user steps, calorie burn, activity minutes, and BMI. Analytical objectives include:
- Behavioral clustering (sedentary, moderately active, highly active)
- Temporal trend analysis (weekday/weekend behavior differentials)
- Health metric evaluation (BMI distribution)
- Predictive insight generation for user engagement strategies

Core Insights

- **Positive Correlation** between steps taken and calories burned (r = 0.44)
- **Sedentary Dominance**: Avg sedentary time = 1030 mins/day vs <10 mins in active categories
- **Temporal Patterns**: Lowest step count consistently on Sundays
- **BMI Range**: Most users lie in the 24–25 (healthy to slightly overweight) category
- **User Segmentation**: 50% users are overweight, indicating potential for personalized coaching

Technical Stack

- **Languages**: Python 3.x
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
- **Methods**:
  - Correlation analysis
  - Feature engineering
  - Temporal segmentation
  - Heuristic-based predictive modeling

Predictive Insights

- Users with <3000 steps/day and >1000 sedentary minutes/day will likely remain inactive without targeted intervention
- Step count directly influences calorie burn—ideal for modeling fitness progression
- Weekend inactivity can be countered via gamified engagement strategies

Business Implications

- **Retention Strategy**: Loyalty rewards for moderately active users
- **Churn Risk**: Sedentary users need beginner-friendly re-engagement nudges
- **Engagement Drop-Off**: Weekend-only challenges can maintain continuous usage



