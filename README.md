# Date Fruit Classification - Machine Learning Project

This project aims to classify seven different types of date fruit using machine learning techniques based on features extracted from images. The dataset contains morphological, shape, and color features derived from 898 images of various date fruit types.

## Dataset Description

The dataset consists of **34 features** related to the external appearance of the fruits, including color, length, diameter, and shape. These features are used to classify seven types of date fruit: Barhee, Deglet Nour, Sukkary, Rotab Mozafati, Ruthana, Safawi, and Sagai.

### Features Explanation:
- **34 numerical features**: These features represent the morphological characteristics of the fruits.
- **Target feature (Class)**: The type of date fruit, categorized as one of the seven classes.

The dataset contains no missing values, and all features are numerical. The goal is to develop machine learning models to classify the date fruits based on these features.

## Machine Learning Models Used

The following models are used in the classification process:
1. **Logistic Regression (LR)**
2. **Artificial Neural Network (ANN)**
3. **LightGBM Classifier (LGBM)**
4. **K-Nearest Neighbors (KNN)**

For each model, hyperparameter tuning is performed using Grid Search to find the best combination of parameters.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/your_repo_name.git
    cd your_repo_name
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook to train and evaluate the models:

    - Train-test split is done with 80% training and 20% testing data.
    - LightGBM and KNN models are tuned and evaluated using Grid Search.
    - Confusion matrices and classification reports are generated to assess model performance.

## Results

The models undergo hyperparameter tuning, and the best parameters for each model are selected based on accuracy. Confusion matrices and classification reports are provided to evaluate the classification performance.

## Confusion Matrix and Classification Report

For each model, after training, the confusion matrix and classification report provide insights into the model’s performance on the test dataset. The overall accuracy, precision, recall, and F1 score for each class are also displayed.

# Contact
For any questions or suggestions, feel free to reach out:

- Email: esragcetinkaya@gmail.com
- LinkedIn: [esragcetinkaya](https://www.linkedin.com/in/esra-gul-cetinkaya/?locale=en_US)
