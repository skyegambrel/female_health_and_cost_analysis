##Female Health and Cost Analysis
An exploratory data analysis investigating the correlation between the female sex and various medical related variables such as US Medical Insurance rate, and BMI. 

##Key Insights
* **Males vs Females:** Males actually pay higher insurance rates on average than females, regardless of any other factors, by roughly $1,400.
* **The Bell Curve:** Females with one child and 5 children paid roughly the same average in insurance rate, with those with no children paying the least on average and those with 3 paying the most on average.
* **Equal BMIs:** Mean BMI remained relatively stable across all groups, suggesting that number of children has no statistically significant effect on average BMI in this dataset.

##Visualizations Showcase

![Cost vs Number of Children](cost_and_children.png)
*Figure 1: Comparative cost analysis showing a non-linear trend between insurance cost and number of children, peaking at 3 children before declining.*

![BMI vs Number of Children](bmi_and_children.png)
*Figure 2: Comparative health metric analysis against number of chilren.*

##Data Stack
* **Language:** Python
* **Libraries:** Pandas (data manipulation), Seaborn & Matplotlib (advanced data visualization)

##Sources
* The dataset used in this project is the **Medical Cost Personal Dataset**, originally sourced from the textbook [*Machine Learning with R*] by Brett Lantz and hosted on [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

##Questions Addressed
1. Do females, regardless of any other factor, pay higher, lower, or equal insurance rates than males?
2. Do females with children pay more or less than females with no children?
3. Do females with more children have higher, lower, or equal BMIs, to those with less or zero children?
