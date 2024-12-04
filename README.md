# NBA Data Science Project

## Team Members:
- Rahul Anantuni
- Ritvik Venkat
- Ben Weatherhead
- Soumil Girdhar
- Anshul Ganumpally

## Contributions:
For each member, list which of the following sections they worked on, and summarize the contributions in 1-2 sentences. Be specific!
- **A:** Project idea
- **B:** Dataset Curation and Preprocessing
- **C:** Data Exploration and Summary Statistics
- **D:** ML Algorithm Design/Development
- **E:** ML Algorithm Training and Test Data Analysis
- **F:** Visualization, Result Analysis, Conclusion
- **G:** Final Tutorial Report Creation
- **H:** Additional (not listed above)

## 2. Introduction
The introduction should motivate your work: what is your topic? What questions are you trying to answer with your analysis? Why is answering those questions important?

## 3. Data Curation
Cite the source(s) of your data. Explain what it is. Transform the data so that it is ready for analysis. For example, set up a database and use SQL to query for data, or organize a pandas DataFrame.

```python
import kagglehub
import pandas as pd
import os
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler, LabelEncoder
from sklearn.ensemble import RandomForestClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report, accuracy_score
from scipy import stats
from scipy.stats import chi2_contingency
```

## 4. Exploratory Data Analysis
(See checkpoint 2.)




## 5. Primary Analysis
Based on the results of your exploration, choose a machine learning technique (e.g., classification, regression, clustering, etc.) that will help you answer the questions you posed in the introduction. Explain your reasoning.

## 6. Visualization
Explain the results and insights of your primary analysis with at least one plot. Make sure that every element of the plots is labeled and explained (don’t forget to include a legend!).

## 7. Insights and Conclusions
After reading through the project, does an uninformed reader feel informed about the topic? Would a reader who already knew about the topic feel like they learned more about it?

If needed, you may add subsections.
