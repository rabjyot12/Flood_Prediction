# Flood_Prediction
Data
The dataset used in this project is sourced from the Playground Series - Season 4 Episode 5 Kaggle competition. It consists of two files:

train.csv: The training data with features and the target variable (FloodProbability).
test.csv: The test data with features, for which predictions need to be generated.
sample_submission.csv: A sample submission file in the required format.
To download the data, you will need a Kaggle account and API key. Once you have the kaggle.json file, you can use the commands in the notebook to download the data.

Running the Notebook
Clone the repository to your local machine or open it in Google Colab.
Install the required libraries (see Setup section).
Obtain the kaggle.json file from your Kaggle account and upload it to your Colab environment as instructed in the notebook.
Run all the cells in the notebook sequentially.
Results
The notebook generates a submission.csv file containing the predicted flood probabilities for the test dataset. The performance of the model on the validation set is evaluated using RMSE.

Note: The RMSE value on the validation set is provided in the notebook output.
## License

This project is licensed under the MIT License - see the LICENSE file for details.
