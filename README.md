# Student Marks Prediction Project

📝 Description
This project is my first end-to-end machine learning model. The goal is to predict a student's exam score based on the number of hours they studied.

🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

 📈 Results
The final trained model uses the formula: **Score = 5.68 * Hours_Studied + 37.73** to make predictions. The visualization below shows how accurately the model's prediction line fits the actual data.
![Final Graph]


<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/8a7cb02d-8d4f-473e-91b6-308b8da5ffd0" />



# Model Validation
To ensure the model performs well on new, unseen data, the dataset was split into a training set (80%) and a testing set (20%). The model was trained only on the training data and then evaluated on the test data.

The key performance metrics on the test set were:
- Mean Absolute Error (MAE): 1.25
- R-squared (R²): 1.00

The low MAE and high R-squared score indicate that the model is highly accurate and reliable for this dataset.
