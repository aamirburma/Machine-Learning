# Iris Dataset Import Example

This repository demonstrates how to import and load the Iris dataset using the `sklearn` library. The Iris dataset is a classic dataset in machine learning, often used for classification tasks.

## Overview

The Iris dataset consists of 150 samples from three species of iris flowers (Setosa, Versicolor, and Virginica). Each sample has 4 features (sepal length, sepal width, petal length, and petal width). This example code demonstrates how to load the dataset and display the first 5 rows of data.

## Prerequisites

Make sure you have the following Python libraries installed:

- `scikit-learn`
- `numpy`

To install the required libraries, run:

```bash
pip install scikit-learn numpy
```

## How to Run

1. Clone this repository to your local machine.

2. Run the script in your terminal or preferred Python environment:

```bash
python iris_dataset_example.ipynb
```

### Code Explanation:

- **Step 1:** Import the `load_iris` function from `sklearn.datasets`.
- **Step 2:** Load the Iris dataset into the variable `data` using `load_iris()`.
- **Step 3:** Print the first 5 rows of the data using `data.data[:5]`.

```python
# Import iris dataset from sklearn library
from sklearn.datasets import load_iris

data = load_iris()  # Load the iris dataset

print(data.data[:5])  # Print first 5 rows of dataset
```

### Output:
The output will display the first 5 rows of the Iris dataset, which includes the features of the first five samples in the dataset.

Example output:

```
[[5.1 3.5 1.4 0.2]
 [4.9 3.  1.4 0.2]
 [4.7 3.2 1.3 0.2]
 [4.6 3.1 1.5 0.2]
 [5.  3.6 1.4 0.2]]
```

## Additional Information

- The dataset contains 150 samples and 4 features for each sample.
- The features are: 
  1. Sepal length (cm)
  2. Sepal width (cm)
  3. Petal length (cm)
  4. Petal width (cm)

- The target variable contains 3 possible species of Iris flowers (Setosa, Versicolor, and Virginica).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


### Key Sections:
- **Overview**: Describes what the code does and the dataset.
- **Prerequisites**: Instructions for installing the necessary dependencies.
- **How to Run**: Instructions on how to run the code.
- **Code Explanation**: A breakdown of what the code does.
- **Output**: Example of what the output will look like.
- **Additional Information**: Provides some additional context about the Iris dataset.