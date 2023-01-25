# Neural_Network_Charity_Analysis
Neural Networks

![image](https://user-images.githubusercontent.com/111101012/214678436-3cce423e-5336-4427-8b04-65d7c1189394.png)

A philanthropic foundation dedicated to helping organizations that protect the environment, improve people's well-being, and unify the world has raised and donated over 10 billion dollars in the past 20 years. This money has been used to invest in lifesaving technologies and organize reforestation groups around the world. Beck's is in charge of data collection and analysis for the entire organization. Her job is to analyze the impact of each donation and vet potential recipients. This helps ensure that the foundations money is being used effectively. 

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively

## Resources

charity_data.csv
AlphabetCoupCharity.ipynb

Data Preprocessing

- What variable(s) are considered the target(s) for your model? 'IS_SUCCESSFUL'

- What variable(s) are considered to be the features for your model? 'IS_SUCCESSFUL'

- What variable(s) are neither targets nor features, and should be removed from the input data? 'NAME'

Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

![Screen Shot 2023-01-25 at 12 17 39 PM](https://user-images.githubusercontent.com/111101012/214680384-8d0d37d5-a729-4685-891f-382fbf8ad6fc.png)

- Were you able to achieve the target model performance? Accuracy was 72%

![Screen Shot 2023-01-25 at 12 18 18 PM](https://user-images.githubusercontent.com/111101012/214680529-c42af51f-e6b2-445e-abcb-5590f4b59aa4.png)

- What steps did you take to try and increase model performance?

## Summary

Accuracy was 72%, recommend testing different models to increase accuracy %
