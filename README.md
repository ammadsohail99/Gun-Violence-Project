# Overview
This project aims to predict and analyze gun violence incidents across the United States using statistical and machine learning techniques. Utilizing a comprehensive dataset of over 260,000 U.S. gun violence incidents from 2013 to 2018, the project seeks to identify patterns, trends, and factors contributing to gun violence. By understanding these factors, we hope to inform policy and contribute to violence reduction strategies.

# Requirements
To successfully run this project, the following are necessary:

R Programming Language: Ensure you have the latest version of R installed. \
RStudio: Recommended for a more interactive development environment. \
Libraries: To run the .rmd file, the following libraries are required:

- tm
- wordcloud
- SnowballC
- ggplot2 
- RColorBrewer
- dplyr
- FNN
- e1071
- GGally
- ggfortify
- ranger
- caret
- gbm
- clustMixType

Please ensure all libraries are installed and updated to their latest versions for optimal performance. Use install.packages("library_name") to install any missing libraries.

# Data Description
## Source
https://www.kaggle.com/datasets/jameslko/gun-violence-data

The dataset encompasses over 260K recorded incidents of gun violence in the U.S. from 2013-2018. Each record includes detailed information about the incident, such as date, location, number of people injured and killed, and potentially the type of guns used. The data provides a granular view of the gun violence problem, which is essential for accurate analysis and prediction.

# Methodology

## Data Preprocessing
Data cleaning and preprocessing involved handling missing values, correcting inconsistencies, and formatting the data for analysis. Key features were extracted and transformed to facilitate effective modeling.

## Model Selection & Methodology
The project employed various statistical and machine learning techniques to analyze the data and predict gun violence trends. Techniques include:

- Tree-based methods (Random Forest, Gradient Boosting Machine)
- Unsupervised Learning (PCA, Clustering)

Each method's performance was evaluated using appropriate metrics, considering the unique aspects of the data and the nature of gun violence incidents.

# Results
- Random Forest: Achieved a Mean Squared Error (MSE) of 0.314 and R-squared value of 74.8% with 500 trees, indicating a robust model for predicting gun violence.
- Gradient Boosting Machine: Completed with a Mean Squared Error (MSE) of 0.315, demonstrating effectiveness in understanding gun violence nuances.
- Clustering: Identified 9 optimal clusters with unique characteristics, revealing patterns like high-intensity incidents and non-lethal aggression in specific areas.

# Conclusion
The predictive analysis, particularly using the Random Forest model, provides a robust foundation for forecasting and understanding gun violence, aiding in more informed policy-making and interventions. Recommendations include utilizing data visualization for public engagement, tailoring interventions to cluster-specific insights, and leveraging technology for education and policy development. These efforts aim to foster a comprehensive understanding and proactive approach to combating gun violence.

# Acknowledgments
This project was a part of a master's program at McGill. Special thanks to the instructors and peers for their guidance and support throughout the project. The dataset used in this project is sourced from Kaggle, acknowledging the data contributors for making this analysis possible.
