# Cancer Cell Data Analysis (Insight Discovery, Stakeholder Recommendations, Predictive Model Construction for Cell Type Classification)



***STATUS:*** **Completed**


## Business Objectives:

As part of the research, the task was to develop a model for the classification of cancer cells based on available medical data. The project aimed to create a tool for more accurate and rapid detection of diseases, which could significantly increase the effectiveness of treatment and save patients' lives.

## Бизнес-Задачи:

1.	Selection of an effective model for the classification of cancer cells into benign or malignant to enhance the efficiency of disease diagnosis and treatment.
2.	Increasing the accuracy of determining the type of cancer cells, which can contribute to the timely initiation of treatment and improve chances of recovery.


## Research Conclusion:

Extensive work was done to analyze cancer cell data, allowing the identification of an optimal boundary for classifying cells into malignant and benign. A classification model was built using logistic regression, which demonstrated high accuracy (0.97 on the test set).


You can see the classification result of the logistic regression model using the ROC-AUC model evaluation on the following graph:

<img src="https://i.imgur.com/wjKIdOx.png" alt="ROC-AUC model"/>

The more the curve covers the upper-left corner of the graph, the better the model classifies the data into categories and avoids both type I and type II errors.

## Application of Research Results:

The results of the work will significantly improve diagnostics and reduce the number of misdiagnoses. The obtained information about dependencies in the data can help doctors make diagnoses much faster in the early stages of treatment.


## Technical Features of the Project:

Various optimization approaches were used to select an effective classification method, but the principal component analysis method proved to be the most effective and was used to obtain the final classification results. Different sets of visualizations were used to choose the data optimization method.


## Project Tools

- Python
- Pandas
- Sklearn
- Matplotlib.pyplot
