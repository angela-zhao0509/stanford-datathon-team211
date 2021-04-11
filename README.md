## 2021 Stanford Open Datathon Project Data Modeling
Datathon information can be found here: https://datathon.stanford.edu/

### Guiding Question
- What are the factors that influence college admission? 
- How might they correlate to each other?
- What should we do to guide graduate applicants to improve admitted chance?

### Dataset
We utilized a dataset from Kaggle about graduate admission: https://www.kaggle.com/mohansacharya/graduate-admissions. Note that this dataset has one limitation that it doesn't contain too much data, and some metrics are evaluated by the applicants thenselve, which might cause a little bias. 

### Exploratory Data Analysis
- Density Histogram
- Histogram
- Boxplot
- Regression Line

### Modeling
We splitted the train and test set with a ratio 80:20 and used 3 classic statistical models to solve classification problem with tuning the best parameters. 
- Logistic Regression: 0.81
- K Nearest Neighbors: 0.78
- Random Forest: 0.83

Codes can be seen in Google Colab Notebook: <a href="https://colab.research.google.com/github/angelazhao2552/stanford-datathon-team211/blob/main/SODP_Team_211.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
### Team Member (Last Name Alphabetically)
- Weiqiao Shen
- Peijia Wang
- Anqi Zhao
- Siyue Zhu
