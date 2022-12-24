# TitanicEDA

Part 1 of Titanic Survival EDA and ML

This project highlights the exploratory data analysis (EDA) of survival using the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic).

Highlights:
* Social class of passenger was significant in survival index. Wealthier passengers (i.e., those who had class 1 tickets) had higher survival than those who had class 3 tickets. This finding is consistent with both male and female passengers. In terms of gender, female passengers had higher survival than male, with mean survival of 74% and 19%, respectively.

![](/images/SurvProbPClassGen.jpg)

* The correlation heatmap of numerical variables revealed significant correlation between Fare and Survival.

![](/images/CorrHeatmap.jpg)

* Survival curve of the passenger age showed peak distributions between ages 0-5 and 20-35.

![](/images/AgeDistSurv.jpg)

### Code and Resources Used
**Python Version:** 3.8.2 (Jupyter Notebook IDE)
**Packages:** pandas, numpy, matplotlib, missingno, seaborn
