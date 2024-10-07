# deep-learning-challenge
Module 21 Challenge
Overview of the Analysis
The purpose of this analysis was to develop a deep learning model capable of predicting the effectiveness of funding applications in the Alphabet Soup dataset. The goal is to determine whether a funding request is likely to be successful based on various features related to the application. 
Results
Data Preprocessing
•	Target Variable(s):
o	IS_SUCCESSFUL: This binary variable indicates whether the funding was used effectively.
•	Feature Variable(s):
o	APPLICATION_TYPE: Type of application.
o	AFFILIATION: Sector of the industry.
o	CLASSIFICATION: Classification of the government organization.
o	USE_CASE: Use case for funding.
o	ORGANIZATION: Type of organization.
o	STATUS: Active status of the application.
o	INCOME_AMT: Income classification.
o	SPECIAL_CONSIDERATIONS: Any special considerations for the application.
o	ASK_AMT: Amount of funding requested.
•	Variables to be Removed:
o	EIN: Identification column, not useful for prediction.
o	NAME: Identification column, not useful for prediction.
Compiling, Training, and Evaluating the Model
•	Model Architecture:
o	Layers: The model was constructed with the following layers:
	Input layer: 40 input features
	Hidden layers:2 layers with 20,10, 10,100,100 neurons respectively
	Output layer: 1 neuron (sigmoid activation for binary classification)
o	Activation Functions: ReLU (Rectified Linear Unit) for hidden layers and Sigmoid for the output layer. ReLU was chosen for its effectiveness.
•	Achieved Performance:
o	Initial models achieved around 72% accuracy. After optimization, the model's accuracy improved to approximately 73% 
•	Steps Taken to Increase Model Performance:
o	Adjusted the number of hidden layers and neurons to capture more complex relationships.
o	Fine-tuned hyperparameters, such as learning rate and batch size.
Summary
The deep learning model developed for predicting funding effectiveness in the Alphabet Soup dataset showed promising results, achieving an accuracy of around 73%. While the initial model struggled with accuracy, iterative improvements in model architecture and hyperparameter tuning led to enhanced performance.

