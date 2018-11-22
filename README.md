# SCS3250-final-project

## Project Description

### About the Dataset
- Description

	This dataset refers to the problem of telemarketing for a bank. The dataset is collected from
	a Portuguese bank and the bank wants to have an effective telemarketing strategy to sell
	long-term deposit accounts (e.g., bonds, saving accounts, etc.). These marketing
	campaigns were based on phone calls and multiple contacts were often needed to
	determine whether a customer would subscribe to a long-term deposit account. Your team of
	data scientists will help this bank in determining such customers and devising an effective
	telemarketing strategy by applying data analytics method on the given dataset.

- Attributes

	| Attribute |                                        Description                                        |                          Type                         |
	|:---------:|:-----------------------------------------------------------------------------------------:|:-----------------------------------------------------:|
	|    Age    |                                    Age of the customer                                    |                        numeric                        |
	|    Job    |                                        Type of job                                        |                      qualitative                      |
	|  Marital  |                                       Marital status                                      |                      qualitative                      |
	| Education |                                 Education of the customer                                 |                      qualitative                      |
	|  Default  |                  Shows whether the customer has credit in default or not                  |                      qualitative                      |
	|  Balance  |                              Average yearly balance in Euros                              |                        numeric                        |
	|  Housing  |                     Shows whether the customer has housing loan or not                    |                      qualitative                      |
	|    Loan   |                    Shows whether the customer has personal loan or not                    |                qualitative/categorical                |
	|  Contact  |              Shows how the last contact for marketing campaign has been made              |                      qualitative                      |
	|    Day    |              Shows on which day of the month last time customer was contacted             |                        numeric                        |
	|   Month   |             Shows on which month of the year last time customer was contacted             |                      qualitative                      |
	|  Duration |                         Shows the last contact duration in seconds                        |                        numeric                        |
	|  Campaign |      Number of contacts performed during the marketing campaign and for this customer     |                        numeric                        |
	|   Pdays   | Number of days that passed by after the client was last contacted from aprevious campaign | numeric, -1 means client was not previously contacted |
	|  Previous |           Number of contacts performed before this campaign and for this client           |                        numeric                        |
	|  Poutcome |                         Outcome of the previous marketing campaign                        |                      qualitative                      |
	|     Y     |      Class attribute showing whether the client has subscribed a term deposit or not      |                   binary: "yes","no"                  |