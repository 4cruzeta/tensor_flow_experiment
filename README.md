# 1. Introduction

## Predict the Introverts from the Extroverts Using TensorFlow

## Objective
The objective of this project is to build a machine learning model using the TensorFlow library to predict whether a person is an introvert or extrovert based on various social and behavioral characteristics. The dataset used for this project is provided by the Kaggle competition.

## Dataset Description
The dataset contains the following columns:

- **id**: Unique identifier for each entry.
- **Time_spent_Alone**: Time the person spends alone, in hours.
- **Stage_fear**: Indicates if the person has a fear of speaking in public (yes or no).
- **Social_event_attendance**: Number of social events attended by the person.
- **Going_outside**: Number of times the person goes outside.
- **Drained_after_socializing**: Indicates if the person feels drained after socializing (yes or no).
- **Friends_circle_size**: Size of the person's circle of friends.
- **Post_frequency**: Frequency of posts on social media.
- **Personality**: The target class, indicating if the person is "Introvert" or "Extrovert".

## Notebook Structure
The notebook will be structured as follows:

1. **Importing Libraries**: We will load necessary libraries such as TensorFlow and Matplotlib.
2. **Loading Data**: We will read the CSV dataset and display a sample.
3. **Data Preprocessing**: 
   - We will check for and handle missing data.
   - Convert categorical variables to numerical format.
   - Split the data into training and validation sets.
4. **Model Building**: We will use TensorFlow's Keras API to create and compile a neural network model.
5. **Model Training**: We will train the model using the training dataset and validate its performance.
6. **Model Evaluation**: We will assess the model's performance using appropriate metrics such as accuracy, recall, and F1-score.
7. **Predictions**: We will use the trained model to make predictions on new data.

## Conclusion
By the end of this notebook, we aim to have an effective model capable of accurately predicting personality traits based on the provided features. This project will allow us to explore the TensorFlow library and apply machine learning techniques to a real-world problem.
