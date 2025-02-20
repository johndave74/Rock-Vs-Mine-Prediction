# Rock-Vs-Mine-Prediction
This project aims to build a prediction system that can classify an object as either a Rock or a Mine using SONAR data. The Logistic Regression model is used for the prediction.

![image](https://github.com/user-attachments/assets/f09bc67b-cae8-4987-a183-c29c148b008a)

# Rock Vs Mine Prediction

This project aims to build a prediction system that can classify an object as either a Rock or a Mine using SONAR data. The Logistic Regression model is used for the prediction.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In this project, we use SONAR data to predict whether an object is a Rock or a Mine. The dataset contains 208 samples with 60 features each. The target variable has two classes: 'R' for Rock and 'M' for Mine.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Data
The dataset used in this project is `sonar_data.csv`. It contains 208 rows and 61 columns. The first 60 columns are the features, and the last column is the target variable.

## Model
We use the Logistic Regression model from scikit-learn to build the prediction system. The data is split into training and testing sets with a 90-10 split.

## Results
The model achieves the following accuracy:
- Training Accuracy: 83.42%
- Testing Accuracy: 76.19%

## Usage
To use this project, follow these steps:

1. Clone the repository:
    ```
    git clone https://github.com/your-username/rock-vs-mine-prediction.git
    ```
2. Navigate to the project directory:
    ```
    cd rock-vs-mine-prediction
    ```
3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook to see the results and predictions.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
