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

- The shape and descriptive statistics for the dataset were displayed using `df.shape` and `df.describe()`.

- A pair plot was created to visualize the relationship between advertising expenditure on TV, Radio, Newspaper, and sales using `seaborn.pairplot`.

- Histograms were plotted to observe the distribution of advertising expenditure on TV, Radio, and Newspaper using `matplotlib.pyplot.hist`.

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
