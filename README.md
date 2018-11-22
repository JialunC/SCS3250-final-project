# SCS3250-final-project

## Project Description

### About the Dataset
- **Description**

	This dataset refers to the problem of telemarketing for a bank. The dataset is collected from
	a Portuguese bank and the bank wants to have an effective telemarketing strategy to sell
	long-term deposit accounts (e.g., bonds, saving accounts, etc.). These marketing
	campaigns were based on phone calls and multiple contacts were often needed to
	determine whether a customer would subscribe to a long-term deposit account. Your team of
	data scientists will help this bank in determining such customers and devising an effective
	telemarketing strategy by applying data analytics method on the given dataset.

- **Attributes**

	| Attribute |                                        Description                                        |                          Type                         |
	|:---------:|:-----------------------------------------------------------------------------------------:|:-----------------------------------------------------:|
	|    Age    | Age of the customer                                                                       |                        numeric                        |
	|    Job    | Type of job                                                                               |                      qualitative                      |
	|  Marital  | Marital status                                                                            |                      qualitative                      |
	| Education | Education of the customer                                                                 |                      qualitative                      |
	|  Default  | Shows whether the customer has credit in default or not                                   |                      qualitative                      |
	|  Balance  | Average yearly balance in Euros                                                           |                        numeric                        |
	|  Housing  | Shows whether the customer has housing loan or not                                        |                      qualitative                      |
	|    Loan   | Shows whether the customer has personal loan or not                                       |                qualitative/categorical                |
	|  Contact  | Shows how the last contact for marketing campaign has been made                           |                      qualitative                      |
	|    Day    | Shows on which day of the month last time customer was contacted                          |                        numeric                        |
	|   Month   | Shows on which month of the year last time customer was contacted                         |                      qualitative                      |
	|  Duration | Shows the last contact duration in seconds                                                |                        numeric                        |
	|  Campaign | Number of contacts performed during the marketing campaign and for this customer          |                        numeric                        |
	|   Pdays   | Number of days that passed by after the client was last contacted from aprevious campaign | numeric, -1 means client was not previously contacted |
	|  Previous | Number of contacts performed before this campaign and for this client                     |                        numeric                        |
	|  Poutcome | Outcome of the previous marketing campaign                                                |                      qualitative                      |
	|     Y     | Class attribute showing whether the client has subscribed a term deposit or not           |                   binary: "yes","no"                  |
	
### Project Requirements

1. **Data Preparation and Pre-prediction Analysis**

	The first and foremost step of data mining process is to understand the data and identify the research question(s). Here are some suggestions to explore and understand datasets:
	- Look at the attribute type; e.g., categorical, ordinal or quantitative
	- Find max, min, mean and standard deviation of attributes.
	- Determine any outlier values (records) for each of the attributes or attributes under
	- Consideration (min, max, std. dev, scatter plots, box plots or others can be used).
	- Analyze the distribution of numeric attributes (normal or other).
	- Plot histograms for attributes of concern and analyze whether they have any influence on the class
	- Try to answer these questions by different visualization techniques:
		- Which attributes seem to be most linked to the class attribute?
		- Which attributes seem to be most linked to the class attribute?
		- Which attributes do you think can be eliminated or included in the analysis?
		- Determine whether the dataset has an imbalanced class distribution (same proportion of records of different types or not).

2. **Predictive Modeling (Classification)**

	After an overall understanding about the dataset, you can use classification algorithms, Decision Tree and Naïve Bayes. Also, choose a classification algorithm of your own choice, explain it a at a high level and compare your results.
	- You will predict the class attribute by using each classification algorithm.
	- Determine the right strategy for dataset split: simple training or testing, 10-fold cross validation, 3-fold cross validation, etc.
	- Repeat the same process for Decision Trees, Naïve Bayes and the third classification algorithm of your choice.
	- Determine your performance measures (accuracy, recall, etc.).
	- Identify which algorithm performs well and in which settings.

3. **Conclusions and Recommendations**

	State your major findings from different sections. State your recommendation to the company that they can put into place to solve their problem.
