# New-York-Property-Anomaly-Detection
In this project, we accepted a request from NY Property to help them detect anomalies in their NY property data records. NY Property Data represents NYC properties assessments for the purpose of calculating property tax, grant eligible properties, exemptions and/or abatements.

Because of the large scale of the dataset, we first examined the data quality and performed exploratory data analysis on some important fields to prepare for the algorithm development in the next step.

Based on the features of this dataset, we conducted feature engineering and dimensionality reduction to develop two unsupervised fraud detection algorithms – Heuristic Algorithm and Autoencoder Algorithm to detect unusual records. 

By combining the ranking scores from these two algorithms, we suggested that the final unusual records that have the biggest possibility to be a fraud record should be 10 records which rank top 10 in the final ranking score. Unreasonable full value and lot area are some features of these unusual records. 

For future analysis of these unusual records, we suggested NYC properties to conduct further research into whether the abnormalities could have a reasonable explanation because of special property categories such as government building, public park, etc.
