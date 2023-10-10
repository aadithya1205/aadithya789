COPPER INDUSTRY PRICE PREDICTION


The data collected in copper industry are have imbalanced data,outliers,noise which affects accuracy of the model

The goal of the project is to get rid of these rubbish data,preprocess and predict the wanted value

workflow of the project:

1.Exploring skewness and outliers in the dataset.

  handle the missing values by filling the null values or deleting the null values

  Identify the skewness of the data

2.Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps

  Encode categorical variables using suitable techniques, such as one-hot encoding, label encoding, or ordinal encoding, based on their nature and relationship with the target variable

3.ML Regression model which predicts continuous variable ‘Selling_Price’ 

  Build as suitable model to predict "selling_price" with highest accuracy

  Evaluvate the model using evaluvatic metrics such as mean square and r square

4.ML Classification model which predicts Status: WON or LOST.

  Build a suitable classification model to classify won or lost with high frequency

  Evaluvate the model using confusion matrix,recall,precision

5.Creating a streamlit page where you can insert each column value and you will get the Selling_Price predicted value or Status(Won/Lost)

   collecting each column and predict value for each model

Through this app,user can input the details in interface and can get predicted value


