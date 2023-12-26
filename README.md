# Project Scenario Overview: Working for Salifort Motors

## About the Company
Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. With a global workforce exceeding 100,000 employees, the company engages in researching, designing, constructing, validating, and distributing electric, solar, algae, and hydrogen-based vehicles. Salifort's unique end-to-end vertical integration model positions it as a global leader at the intersection of alternative energy and automobile industries.

## Business Case
As a data specialist at Salifort Motors, you have been entrusted with the results of a recent employee survey. The senior leadership team has assigned you the task of analyzing the data to generate ideas for enhancing employee retention. Specifically, they have requested the design of a model capable of predicting whether an employee is likely to leave the company. This prediction is to be based on various factors, including department, number of projects, average monthly hours, and any other data points you consider relevant.

##  Deliverable
 The `purpose` is to analyze a dataset and build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm.And study what makes employees leave the organisation and strengthen retention of Employees

## Dataset
Dataset has been taken from Kaggle and can be found [here](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)

##### Snapshot of dataset
![](https://res.cloudinary.com/dvfjbyf7s/image/upload/v1703581626/HR%20Analytics/Dataset.png)



### EDA (Exploratory data exploration)
Data was searched for missing values.
Patterns in data was shown usign Seaborn charts.
Outliers were found and operated for model prediction.


## Modeling
Logistic Regression was chosen as model

#### Here is Logistic Regression Model Performance
![](https://res.cloudinary.com/dvfjbyf7s/image/upload/v1703580221/Final_Results_vn2j2l.png)


>1 is left the organisation

>0 is stayed in the organisation

**So the model correctly predicted  126 (1s), and 2164 (0s)**
**And predicted wrong 346 (1s) and  157 (0s)**


### Summary 

**Logistic Regression**

The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set.

### Conclusion, Recommendations, Next Steps

The models and the feature importances extracted from the models confirm that employees at the company are overworked. 

To retain employees, the following recommendations could be presented to the stakeholders:

* Cap the number of projects that employees can work on.
* Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied. 
* Either reward employees for working longer hours, or don't require them to do so. 
* If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. 
* Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts. 
* High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort. 
