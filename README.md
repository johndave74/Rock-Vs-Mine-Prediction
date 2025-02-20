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

Rock vs. Mine is a machine learning project that uses sonar to distinguish between rocks and mines underwater. The project's goal is to improve the safety of underwater operations by reducing human error and enhancing situational awareness. 
### How it works
- A submarine sends out a sound signal using sonar 
- The submarine receives and analyzes the signal that bounces back 
- The system uses machine learning to classify the object as a rock or a mine

### Applications
The Rock vs. Mine project has applications in marine exploration, defense, and resource extraction. 

### Benefits 
- Improved accuracy: The system can analyze complex patterns in sonar data, which can be difficult to do manually
- Streamlined detection: The system can automate the classification of rock and mine formations, making the process more efficient
- Enhanced situational awareness: The system can help reduce human error and improve decision-making
- 
### Related resources
- Rock vs. Mine Prediction on GitHub: Includes a dataset, data visualization techniques, and a train-test split to evaluate model performance 
- SONAR Rock vs Mine Prediction: A machine learning classification project that uses sonar data 
- SONAR Rock vs Mine Prediction Using Machine Learning: A project that uses logistic regression to differentiate underwater objects 

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
