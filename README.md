# House-price-prediction-in-USA
This project is about predicting the price of a house based on different parameters of the house. We have used **LinearRegression** model from the sklearn library.

# Required Libraries
1. Pandas
2. Numpy
3. Matplotlib
4. Sklearn

# Features
- **Machine Learning Model**: Built using the LinearRegression Model , which is based on continuoes linear regression.
- **Evaluation**: The trained model is evaluated on various parameters like **Mean Absolute Error**, **Mean Squared Error**, **Root Mean Squared Error** etc.

# Dataset
The dataset is collection of various features of the house like:
1. date of recording the data of the house.
2. No. of bedrooms
3. No. of bathrooms
4. Living area in squarefeet
5. Lot area in squarefeet
6. Floors in a house
7. Does have a waterfront
8. View of the house
9. Comdition of the house
10. Square feet of the house above
11. Square feet of the house basement
12. Year of the house built
13. Year of house being renovated
14. Street in which the house is located in
15. City in which the house is located in
16. StateZip of the house
17. Country of the house

The output is the price of the house

# Preprocessing of the Data
- The date of the house is removed as it is not important.
- All the object columns are encoded using the One Hot Encoder.
- All the numeric columns are scaled using the MinMaxScaler.

# Model Training
The Model is trained on the preprocessed dataset. Only the 80% of the dataset is used for training and remaining is used for testing. This is easily handled by the **train test split** class from the sklearn library.

# Instructions
1. **Clone the repo**
   ```bash
   git clone https://github.com/vamshi2011/House-price-prediction-in-USA.git
   ```
2. **Launch the application**
   ```bash
   python House_price_prediction.ipynb
   ```
# Open in google collab
To open the application directly in google collab , go to **"House_price_prediction.ipynb"** file in github and click the **"Open in Google collab"**. There you can edit the code as per your reqirements.
