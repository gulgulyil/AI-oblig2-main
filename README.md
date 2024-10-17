
## **Assignment Description**:

* Tesla-Stock-Price-Prediction- Make a prediction algorithm which predicts the price of this stock on a specific date. Input will be date and output should be price of that stock (close value in the data file).
You should also show the prediction percentage score.

* Explore and research which algorithm would work best for this use case (regression or classification)  
We used the refrasjon algorithm. Because we needed to make inferences about future prices based on the data we had so far. When it comes to prediction, the regression algorithm is more appropriate.


Gülnur Yildiz- s374961 
Somayeh Fattahi- s371482 
Nasima Josefi- s354388 
Rayan Nabaz Kanabi- s375057

#Questions:

How well does your model perform?
Our initial model had a Mean Squared Error (MSE) of 21439.15 and an R² Score of 0.41, indicating limited predictive capability. In contrast, after applying the Random Forest algorithm, we achieved a MSE of 40.37 and an R² Score of 0.999. This shows a significant improvement, with the Random Forest model explaining nearly all the variance in Tesla's closing prices, highlighting its superior performance.

Are there any improvements you can make?
While the Random Forest model shows excellent performance, further enhancements could include testing even more advanced algorithms like XGBoost. Expanding the dataset and integrating additional features, such as market trends or economic indicators, could lead to even better results.

What happens if you remove features and predict again?
The Random Forest model currently relies on a broader set of features, so removing any of them might reduce its performance. However, if we identify and remove irrelevant features after incorporating new data, it could enhance the model's accuracy and generalization by minimizing overfitting.

Reference :
Microsoft. (2024, August 28). What is automated machine learning (AutoML)? Microsoft Learn. https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml?view=azureml-api-2 