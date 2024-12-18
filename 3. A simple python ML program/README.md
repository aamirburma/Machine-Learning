# Iris Dataset Classification with Decision Tree

This project classifies iris flowers into three species based on four features: sepal length, sepal width, petal length, and petal width using a **Decision Tree Classifier**. The classification is performed on the **Iris dataset**, a well-known dataset used for machine learning tasks.

## Prerequisites

Before running this project, make sure you have the following Python libraries installed:

- `scikit-learn`
- `pandas`
- `numpy`

You can install the necessary dependencies by running the following command:

```bash
pip install scikit-learn pandas numpy
```

## Dataset

The dataset used in this project is the **Iris Dataset**, which is available in the `sklearn.datasets` module. It contains 150 samples of iris flowers, classified into 3 species:
- Setosa
- Versicolor
- Virginica

Each sample contains 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Steps Involved

1. **Data Loading**: The Iris dataset is loaded using `load_iris()` from scikit-learn.
2. **Data Splitting**: The dataset is split into training and testing sets using `train_test_split()`. 70% of the data is used for training, and 30% is used for testing.
3. **Model Creation**: A Decision Tree Classifier is created using `DecisionTreeClassifier()`.
4. **Model Training**: The classifier is trained using the training data (`X_train`, `y_train`).
5. **Prediction**: Predictions are made using the testing data (`X_test`).
6. **Evaluation**: The accuracy of the model is evaluated using `accuracy_score()`.

## How to Run the Code

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/aamirburma/Machine-Learning.git
   ```

2. Navigate to the project directory:
   ```bash
   cd "3. A simple python ML program"
   ```

3. Open the `iris_classifier.ipynb` Jupyter notebook in your favorite IDE (such as Jupyter Notebook, VS Code, etc.).

4. Run the notebook cells in sequence to load the data, train the model, and evaluate the results.

## Result

After running the notebook, the model will output the accuracy score, which indicates how well the Decision Tree Classifier has performed in classifying the iris species based on the features provided.

## Contributing

Feel free to fork this repository, submit issues, and create pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.