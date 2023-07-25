# deep-learning-challenge

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model? I had used CLASSIFICATION as a target for my model.
What variable(s) are the features for your model? I had used IS SUCCESSFUL as the Features for my model.
What variable(s) should be removed from the input data because they are neither targets nor features? NAME and EIN was removed.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? I had used 2 hidden layers with 100 and 50 neurons. For the optimization I had used 3 hidden layers with two different sets of neurons. Optimization with dropping EIN and NAME I had used 3 hidden layer with 50, 25, 30. Optimization with dropping only EIN I had used 3 hidden layers with 100, 50 and 25 neurons.
Were you able to achieve the target model performance? I was not able to acheive the target model performance.

What steps did you take in your attempts to increase model performance? I had change the epouch to 100, 50 and 25.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Here is the result of my Accuracy. Target was to get 75%. Which my model did not acheive. I would prefer different model for this classification problem.

268/268 - 2s - loss: 0.5782 - accuracy: 0.7270 - 2s/epoch - 9ms/step
Loss: 0.5781957507133484, Accuracy: 0.7269970774650574