# venture_funding_with_deep_learning

In this project, we use the TensorFlow library to create and train a binary classification deep learning model on a dataset containing data on various applicants. The aim is to predict whether an applicant will be successful based on the features in the dataset. The model is compiled, trained, and evaluated for accuracy. We also create two alternative models and compare their performance to the original.

The project uses the pandas library for data cleaning and preprocessing, sklearn for data scaling and splitting into training and test datasets, and TensorFlow's Keras for designing and training the neural network.

## Project Files

- `applicants_classification.ipynb`: This is the main Jupyter notebook containing the code for data preprocessing, model creation, compilation, training, and evaluation.

- `applicant_data.csv`: This is the dataset used for the project. 

## Steps to Run the Jupyter Notebook

1. Clone the repository and navigate to the downloaded folder.

2. Install the required packages.

3. Launch Jupyter Notebook

4. In the Notebook Dashboard, navigate to the repository folder, and open the `applicants_classification.ipynb` notebook.

5. Run each cell in the notebook to see the output.

## Models

The project includes one original model and two alternative models. All models are deep neural networks built using TensorFlow's Keras. The original model has two layers, while each alternative model has an added complexity:

- `Original Model`: This model has two layers. The first layer has 80 neurons, and the second layer has 30 neurons. The 'relu' activation function is used for the first layer, and the 'sigmoid' activation function is used for the second layer. 

- `Alternative Model 1`: This model has two layers. The first layer has an increased number of neurons (120), and the second layer has 30 neurons. Both layers use the 'relu' activation function.

- `Alternative Model 2`: This model has three layers, with the first two layers having 160 neurons each and the third layer having 80 neurons. All layers use the 'relu' activation function.

After training each model, they are evaluated for accuracy and loss on the test data.

## Results

The results of the model evaluations, including the accuracy and loss on the test data, are printed in the last section of the notebook. You can compare these results to understand which model performs the best on this dataset. Each model is also
