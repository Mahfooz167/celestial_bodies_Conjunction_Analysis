# celestial_bodies_Conjunction_Analysis
![](https://csps.aerospace.org/sites/default/files/styles/card/public/2023-01/CSPS%20Cover_Enabling%20a%20New%20Space%20Paradigm%20%2811049%29_THUMBNAIL.jpg?h=06ac0d8c&itok=wz93qwmn) 


## Author: Md Mahfooz Alam Ansari
## Company: Digantara
## Domain: Data Science/Data Analyst

### Aim

The primary aim of this project is to conduct a comprehensive analysis of conjunctions among Resident Space Objects (RSOs) in Earth's orbit. The analysis focuses on predicting potential collision scenarios by examining the dataset of predicted conjunctions sourced from CelesTrak.

### Objectives:

The project aims to contribute to the understanding of conjunction events in space, providing valuable insights for space agencies and satellite operators. By identifying influential factors and trends, this analysis aims to enhance satellite safety protocols, ensuring the sustainability and security of satellite missions amidst the growing space environment

### Libraries Used

The following important libraries were used for this project:

- `numpy`
- `pandas`
- `matplotlib.pyplot`
- `seaborn`


### Dataset

The dataset was loaded using pandas as a DataFrame from the file "/content/sort-minRange.csv."

### Data Exploration and Preprocessing

1. Data Overview
Dataset Description: The dataset comprises predicted conjunctions among Resident Space Objects (RSOs) in Earth's orbit, sourced from CelesTrak, containing details like Time of Closest Approach (TCA), relative speeds, object IDs, and probabilities.
Initial Assessment: Explored the dataset's structure, dimensions, and identified columns relevant to the analysis.
2. Handling Missing Values
Null Values: Detected and addressed missing values, primarily in 'OBJECT_NAME_2', 'DSE_2', 'TCA', 'TCA_RANGE', 'TCA_RELATIVE_SPEED', 'MAX_PROB', and 'DILUTION' columns.
Approach: Employed techniques such as imputation or removal of missing entries based on their impact on subsequent analyses.
3. Data Cleaning and Formatting
Data Consistency: Checked for inconsistencies, ensuring uniformity in data formats, object IDs, and timestamps (TCA).
Standardization: Formatted timestamps into a uniform datetime format for ease of analysis and comparison.
4. Feature Selection and Engineering
Relevance Assessment: Evaluated column significance for correlation analysis, focusing on 'TCA', 'TCA_RANGE', 'TCA_RELATIVE_SPEED', 'MAX_PROB', 'DILUTION', and relevant object identifiers.
Derived Features: Calculated derived features if needed, possibly integrating new variables based on domain expertise or specific analytical needs.
5. Exploratory Data Analysis (EDA)
Statistical Summary: Generated descriptive statistics, such as mean, median, and standard deviation, to understand the dataset's central tendencies and variations.
Visualization: Utilized histograms, scatter plots, and count plots to visualize distributions and relationships between key variables.
6. Data Preprocessing
Normalization/Scaling: Standardized numerical features, ensuring their range consistency for improved model performance.
Categorical Encoding: Encoded categorical variables if required, converting them into numerical representations.
### Correlation Analysis
TCA Range & Collision Probability:
Wider Time of Closest Approach (TCA) ranges often correlated with lower collision probabilities, suggesting increased separation might reduce collision likelihood.

Relative Speed & Collision Risks:
Higher relative speeds between RSOs indicated higher collision risks, potentially due to increased impact energy during potential collisions.

Dilution & Prediction Accuracy:
Lower dilution values, indicating higher certainty in predicting conjunction events, aligned with more accurate collision predictions, emphasizing the importance of certainty in risk assessment.

Object Types & Collision Probability:
Variances in collision probabilities were noticed among different object types (satellites, debris), highlighting diverse risk profiles across classifications.
Temporal Correlations:


### Contact

If you have any questions or need further assistance, feel free to contact the author, Md Mahfooz Alam Ansari.

Thank you !
