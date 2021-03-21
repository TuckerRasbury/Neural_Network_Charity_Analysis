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
        - The target variable in our dataset is as follows: IS_SUCCESSFUL.

    - What variable(s) are considered to be the features for your model?
        - The variables considered features in our model are as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

    - What variable(s) are neither targets nor features, and should be removed from the input data?
        -   The variables that are neither targets nor features are as follows: EIN and NAME.

##### Establishing the Target and Features in the Code

![](/Images/target_values.png)

##### Variables that are neither Targets or Features 

![](/Images/external_to_model_values.png)

- Compiling, Training, and Evaluating the Model

The details below detail I approached my most successful model, attempt 3. After my second model, the accuracy stayed relatively the same. The change between the first and second models was the frequency at which I saved the model's weights.

    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
        - I used approximately 125 neurons, three layers, and a "relu" activation function. Given the high number of variables, I u
        
    - Were you able to achieve the target model performance?
        - Unfortunately, I was not able to achieve the target model performance of 75%. I was able to achieve a 72% accuracy rate, 3% short of the target model performance.

    - What steps did you take to try and increase model performance?
        - To increase model performance, I used three hidden layers and 125 neurons in the hidden layers. The risk of this was overfitting, but given the accuracy rate, I am fairly confident the model did not overfit the training dataset.

##### Model

![](/Images/model.png)

##### Model Evaluation

![](/Images/model_evaluation.png)

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
