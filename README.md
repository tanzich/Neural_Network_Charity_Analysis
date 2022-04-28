# Neural_Network_Charity_Analysis

## Overview of the analysis
The purpose of this project is to use Machine Learning and Neural Networks together with Tensorflow to analyze and understand if the applicants that will be funded by Alphabet Soup will be successful.

### Method of analysis
- Preprocessing the data for the neural network
- Compile, train and evaluate the model
- Optimize the model

## Results

### Data Processing:
- Columns EIN and NAME are identification information and have been removed from the input data.

- Column IS_SUCCESSFUL is considered as the target for my deep learning neural network.

### Compiling, Training, and Evaluating the Model:

#### Attempt 1:
- For my first attempt, I tried with two hidden layers with 80 and 30 neurons respectively.The model accuracy was 62.45%

- To improve this, I tried bucketing to the feature ASK_AMT, and change the hidden layers with 100 and 30. This did help Increase performance and the model acuracy was 72.97%

- To improve even further I updated the hidden layers and added another hidden layers, with values 80, 30, 10 respectively. This helped to improve performace to 73.21%


## Summary

I couldnt improve the performace above 75% in three attempts. We could further optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Another solution would be to use the Random Forest classifiers.