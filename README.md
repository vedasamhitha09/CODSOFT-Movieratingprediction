Predict movie rating using machine learning algorithms based on the dataset.

 Movie Rating Prediction:

This repository contains the script that predicts the movie rating from regression techniques.The dataset used is the IMDb Movies India from Kaggle.

 Dataset:

The dataset contains information about the passengers such as Genre,Rating,Director and other variables. 


 Usage:

To predict the rating for a movie, run the script and provide movie dataset details when prompted.

Example:

data={'Year':[2019],'Votes':[36],'Duration':[111],'Genre_mean_rating':[5.8],'Director_encoded':[4.5],'Actor1_encoded':[5.3],'Actor2_encoded':[4.5],'Actor3_encoded':[3.5]}

trail=pd.DataFrame(data)

rating_predicted=Model.predict(trail)

print("Predicted Rating:",rating_predicted[0])
