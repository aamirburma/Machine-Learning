# Shape Recognition Using Decision Tree Classifier

This project demonstrates the use of a Decision Tree Classifier to classify shapes based on the number of sides. The dataset contains several shapes such as Triangle, Square, Rectangle, Pentagon, Hexagon, etc., along with their respective number of sides. The model uses this dataset to train and classify shapes based on the number of sides provided as input.

The project is implemented in a Jupyter notebook `shape_recognition.ipynb`.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Code Walkthrough](#code-walkthrough)
- [Example](#example)
- [License](#license)
- [Colab](#colab)

## Description

This project utilizes a simple dataset where the number of sides of various shapes is used as input data to classify the corresponding shapes using a Decision Tree Classifier. The dataset includes common shapes and their respective number of sides (e.g., Triangle, Square, Pentagon). The Jupyter notebook `shape_recognition.ipynb` demonstrates data preparation, model training, testing, and prediction for new inputs.

## Installation

To run this project, you'll need to have Python installed, as well as the necessary dependencies. The recommended way to install the dependencies is by using `pip`.

### Step 1: Clone the Repository

You can clone the repository to your local machine using the following command:

```bash
git clone https://github.com/aamirburma/Machine-Learning.git
```

### Step 2: Navigate to the Project Directory

Once you've cloned the repository, navigate to the project directory:

```bash
cd "Machine-Learning/1. Shape Recognition using Decision Tree Classifier"
```

### Step 3: Install Dependencies

Use `pip` to install the necessary dependencies:

```bash
pip install pandas scikit-learn
```

## Dependencies

- `pandas`: A powerful library for data manipulation and analysis.
- `scikit-learn`: A machine learning library for implementing and evaluating the Decision Tree Classifier.

## Usage

1. Clone the repository as described above.
2. Navigate to the directory `1. Shape Recognition using Decision Tree Classifier`.
3. Launch the Jupyter notebook:

   ```bash
   jupyter notebook shape_recognition.ipynb
   ```

4. The Jupyter notebook will open in your default browser, and you can execute the cells to run the machine learning pipeline.

## Code Walkthrough

1. **Dataset**: The dataset consists of shapes and their number of sides.
2. **Feature and Label Separation**: The number of sides is used as the feature (input), and the shape name is the label (output).
3. **Train-Test Split**: The data is split into training and testing sets using an 80-20 split.
4. **Model Training**: The Decision Tree Classifier is trained on the training data.
5. **Prediction**: The trained model is used to predict the shape for a given number of sides.
6. **Evaluation**: The model's accuracy is evaluated on the test data.

## Example

Here's an example output from running the notebook:

```bash
Model accuracy: 100.00%
The predicted shape for 4 sides is: Square
```

In this example, the model correctly identifies the shape with 4 sides as a "Square."

## Colab

You can also run the notebook on Google Colab by clicking the following link:

[Open in Google Colab](https://colab.research.google.com/drive/1-dhtV0Hivb6U2UBi2pHZzj_edIcI0EMl?usp=sharing)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.