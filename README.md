# Fall-2020-MLADS-Labs-2020-LAB-DataDrift
Data Drift
MLADS-Data-Drift-Tutorial
Scalable Data drift using Azure Machine Learning and Azure Data bricks Description Data drift is one of the top reasons model accuracy degrades over time. For machine learning models, data drift is the change in model input data that leads to model performance degradation. Monitoring data drift helps detect these model performance issues apriori. Causes of data drift include:

Upstream process changes like metric definition changes Data quality issues, such as a broken CRM system which shows Revenue as null Natural drift in the data, such as Revenue changing across quarters or due to external environment like COVID Our goal in this tutorial is to convey a theoretical and practical aspect of data drift used for in-production models in a scalable & efficient manner. The learnings can be applied for any machine learning model in any business.

We will talk about the power of Azure Machine Learning which simplifies data drift detection by computing a single metric abstracting the complexity of datasets being compared. These datasets may have hundreds of features and tens of thousands of rows. Once drift is detected, you can drill down into which features are causing the drift. You then inspect feature level metrics to debug and isolate the root cause for the drift. This top down approach makes it easy to monitor data instead of traditional rules-based techniques. All this can be done for multiple models in an automated way leveraging the power of Azure Data Bricks and Azure ML.

The fundamental idea this tutorial will aim to convey is that incorporating Data drift for machine learning model would help in detecting model performance degradation apriori and reduce the cost of prediction gone wrong in a scalable and automated way.
