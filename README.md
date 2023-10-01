# deep-learning-challenge



### Overview of the analysis:

The objective of this project is to develop a binary classifier tool using machine learning techniques to aid Alphabet Soup, a nonprofit foundation, in identifying the most promising funding applicants for their initiatives. The dataset employed in this analysis comprises diverse metrics from 34,000 organizations that have received support from Alphabet Soup

    - Data Preprocessing
    - Model Compilation, Training, and Evaluation
    - Model Optimization

#### Data Preprocessing:

    In this stage, we prepare and clean the data to make it suitable for training a neural network.

#### Model Compilation, Training, and Evaluation:

    We proceed with the compilation, training, and evaluation of the machine learning model. This phase involves selecting appropriate loss functions, optimizers, and performance metrics to assess the model's effectiveness.

#### Model Optimization:

    The final step revolves around optimizing the model's architecture and hyperparameters to enhance its predictive capabilities and overall performance.

### Results:

#### Data Preprocessing
    - We removed the 'EIN' and 'NAME' columns because they didn't contain useful data for the model.
    - We set 'IS_SUCCESSFUL' as the target variable.


#### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

    Since we have a mix of categorical and numerical features, I used an input layer with the number of neurons equal to the total number of unique values across all categorical columns. In my case, it's 17 + 6 + 71 + 5 + 4 + 9 = 112 neurons for the categorical features.

    I used with 2  hidden layers.

    For the output layer, since it's a binary classification problem (IS_SUCCESSFUL), I used a sigmoid activation function.

    For binary classification, I used 'binary_crossentropy' as the loss function

    
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.