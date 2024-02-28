## Income-Trends-Census-Analysis

# Introduction:
In the era of data-driven insights, the Census Income dataset serves as a key resource for unraveling socio-economic complexities. Comprising demographic features such as age, education, and occupation, it forms the foundation for a classification problem for predicting income levels. Our aim here is to try and leverage the predictive potential of this information to discern patterns influencing an individual's income, specifically predicting whether it exceeds $50,000 annually.

# Problem Statement:
A critical challenge in socio-economic research revolves around the absence of a robust predictive model to find the intricate factors shaping individual income levels. The inability to forecast accurately hampers targeted interventions and informed decision-making, limiting our capacity to address income disparities effectively. By uncovering hidden patterns within demographic attributes, we hope to contribute to the enhancement of socio-economic decision-making, offering a nuanced approach to address the challenges associated with income disparities.

# Data Source:
Link to the UCI repository: https://archive.ics.uci.edu/dataset/20/census+income

# Conclusion:
Using the Census Income information, we set out to create an excellent prediction model for identifying income levels. After experimenting with many machine learning methods, including K-Nearest Neighbors (KNN) clustering, Support Vector Machines (SVM), Naive Bayes, and Logistic Regression, the findings show that Logistic Regression is the best resilient and accurate approach for the task.

# Key findings:
1. Accuracy Comparison:
Logistic Regression outperformed KNN, SVM, and Naive Bayes in predicting income levels based on demographic variables, with an outstanding 85% accuracy.

2. Interpretability and simplicity:
Logistic Regression is not only accurate, but also interpretable, which makes it easier to comprehend the link between input data and projected outcomes. This simplicity might be critical for stakeholders looking for insights into the issues driving income forecasts.

3. Efficiency of Training and Inference:
Logistic regression often has faster training times than more sophisticated algorithms such as SVM. It demonstrates efficiency in both model training and prediction, making it suited for real-time applications or scenarios involving large data sets.
