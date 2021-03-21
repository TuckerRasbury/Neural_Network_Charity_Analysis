# Neural_Network_Charity_Analysis

## Overview of the Analysis
Using machine learning and neural networks, I built a binary classifier that is capable of predicting whether applicants will be successful if funded by a hypothetical grant issuing institution that herein is referred to as AphabetSoup. The original dataset provided by AlphabetSoup contained information on 34,000 organizations that have received funding from them over the years. After three attempts, I was able to build a binary classifier that could predict an organization's success after being funded with a 72% accuracy rate.

### Tools and Resources Used
- Resources
    - Data available for download: [Charity_data.csv](https://github.com/TuckerRasbury/Neural_Network_Charity_Analysis/raw/main/Resources/charity_data.csv)
- Tools
    - Python & Python Libraries:
        - [Panadas](https://pandas.pydata.org/), [os](https://www.geeksforgeeks.org/os-module-python-examples/#:~:text=The%20OS%20module%20in%20Python,using%20operating%20system%2Ddependent%20functionality.&text=path*%20modules%20include%20many%20functions%20to%20interact%20with%20the%20file%20system.), [Tensorflow](https://www.tensorflow.org/learn), [Scikit Learn](https://github.com/scikit-learn/scikit-learn)

## Results

- Initial Data

The variables initially in the dataset were as follows:

    - EIN and NAME — Identification columns
    - APPLICATION_TYPE — Alphabet Soup application type
    - AFFILIATION — Affiliated sector of industry
    - CLASSIFICATION — Government organization classification
    - USE_CASE — Use case for funding
    - ORGANIZATION — Organization type
    - STATUS — Active status
    - INCOME_AMT — Income classification
    - SPECIAL_CONSIDERATIONS — Special consideration for application
    - ASK_AMT — Funding amount requested
    - IS_SUCCESSFUL — Was the money used effectively

- Data Preprocessing
    - What variable(s) are considered the target(s) for your model?
     - The target variable in our dataset is IS_SUCCESSFUL.
    - What variable(s) are considered to be the features for your model?
     -   
    - What variable(s) are neither targets nor features, and should be removed from the input data?
     -   

![](/Images/target_values.png)
![](/Images/external_to_model_values.png)

- Compiling, Training, and Evaluating the Model
    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Were you able to achieve the target model performance?
    - What steps did you take to try and increase model performance?

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
