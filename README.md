# DeepLaerning_Aiswarya_Jayaprakash
Diabetes Progression Prediction Using ANN

This project aims to build and evaluate an Artificial Neural Network (ANN) to predict diabetes progression using various patient features. The dataset is the well-known Diabetes dataset from sklearn, and the goal is to help healthcare professionals understand how different factors influence diabetes progression.
Objective:

    Predict diabetes progression using a neural network model.
    Evaluate the model’s performance using metrics such as Mean Squared Error and R-squared Score.
    Improve the model through hyperparameter tuning and architectural changes.

Steps:

    Loading and Preprocessing:
        The dataset was loaded and normalized using StandardScaler for optimal model performance.

    Exploratory Data Analysis (EDA):
        Visualizations of feature distributions and relationships with the target variable were performed using Seaborn and Matplotlib.

    ANN Model Building:
        A basic ANN was built using Keras, consisting of one hidden layer with relu activation and one output layer for regression tasks.

    Model Training:
        The ANN model was trained using the Adam optimizer and MSE as the loss function over 100 epochs.

    Model Evaluation:
        The model was evaluated on testing data, with performance measured by MSE and R-squared.

    Improving the Model:
        An improved model was created by experimenting with additional layers and neurons, which resulted in better performance.

Results:

    The original and improved models were compared, with significant performance gains from the improved architecture.
