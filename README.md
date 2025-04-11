# deep-learning-challenge
Data Bootcamp Week 21 HW

# Overview and Purpose
Utilizing data provided by the nonprofit foundation, Alphabet Soup, the goal of this is to create a tool to select applicants for funding with the likelihood of success. In order to achieve this a machine learning model and neural networks with a binary classifier will assist with making these decisions. From the data, the model will utilize features such as application type, organization type, income level, and funding amount to classify applicants as successful or not. The analysis involves multiple steps including, preprocessing the data, designing and evaluating a neural network, and optimizing a model to achieve a target accuracy. This will help Alphabet Soup make more data driven informed decisions.






## Results ##


# Data Preprocessing
- What variable(s) are the target(s) for your model?
   - The target variable for the model is "IS_SUCCESSFUL"


- What variable(s) are the features for your model?
   - These include the columns that were not dropped: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
   - Columns that were dropped are: EIN and NAME


- What variable(s) should be removed from the input data because they are neither targets nor features?
   - These were the columns that were dropped: EIN and NAME






# Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - There was an input layer, 2 hidden layers, and an output layer.
   - For the first hidden layer there were 100 neurons and for the second layer there was 40 neurons.
   - This provided a strong baseline for accuracy.


- Were you able to achieve the target model performance?
   - Through optimization techniques there was a slight improvement with the target model performance. This included adding an additional hidden layer with 10 neurons.
   - This led to a slight improvement in performance.




- What steps did you take in your attempts to increase model performance?
   - Adjusted the model structure with an additional hidden layer with 10 neurons.
   - Continued with the same activation function.
   - This increased the model accuracy by 1%




# Summary
The machine learning model and neural networks has potential to aid Alphabet Soup's decision making of funding. The original baseline neural network had two hidden layers that produced a decent performance and then through optimization the neural network improved performance by 1%. A tree based model couple potentially offers better performance with more structured data. Continuing to improve the neural network will assist with data-driven decisions.
