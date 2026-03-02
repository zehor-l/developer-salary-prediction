# developer-salary-prediction
Developer salaries vary widely across roles, regions, and skill sets. In this project, We analyze the 2023 Stack Overflow Survey to uncover the key factors influencing compensation, combining exploratory data analysis, feature engineering, and regression modeling to identify meaningful patterns in real-world survey data.

##📊 Analysis Summary

- The model explains 56.5% of salary variance (R² = 0.565), performing well for typical developer salaries.

- Best performance occurs in the $50k–$150k range (mean error ~$22k–$31k).

- Predictions for US developers are less accurate, likely because regional salary variation is not captured (e.g., Silicon Valley vs other states).

- Heavy reliance on geographic features suggests location is a dominant driver of compensation.

- Linear regression provides interpretability but struggles with extreme values and feature interactions.
