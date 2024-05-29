Crop Recommendation
Overview
This project aims to develop a crop recommendation model based on soil composition and environmental factors. By analyzing key features such as nitrogen, phosphorus, potassium content in the soil, temperature, humidity, pH value, and rainfall, the model predicts the most suitable crop for a particular region.
Dataset
The dataset consists of the following features:
•	N: Nitrogen content in the soil
•	P: Phosphorus content in the soil
•	K: Potassium content in the soil
•	Temperature: Temperature (in Celsius)
•	Humidity: Humidity (in %)
•	pH: pH value of the soil
•	Rainfall: Rainfall in the particular region (in mm)
Target variable:
•	Crop: Crop suitable to grow in the particular region considering all the factors
Model Training
•	Data Preprocessing: Missing values are handled, Categorical variables are encoded, Numerical features are scaled
•	 Splitting Data: The dataset is split into features (X) and the target variable (y), A train-test split with an 80:20 ratio is performed.
•	Model Selection: Various classifications of algorithm are involved
	Logistic Regression
	Naive Bayes
	Support Vector Machine
	K-Nearest Neighbors
	Decision Tree
	Random Forest
	Bagging
	Gradient Boosting
•	Training and Evaluation: Each model is trained on the training data, Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated on the test data, the model with the best performance across all metrics is selected as the best mode.
Usage: To use the trained model for prediction:
1.	Clone the repository to your local machine.
2.	Load the trained model using the provided file (model.pkl).
3.	Prepare input data with the same features used during model training.
4.	Use the loaded model to make predictions on the input data.

Files
•	model.pkl: Trained model file.

