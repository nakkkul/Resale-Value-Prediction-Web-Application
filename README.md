**Resale Value Prediction Web Application**

This project is a machine learning-powered web application that predicts resale values for vehicles based on user-inputted information. Built using Flask for the backend and HTML for the frontend, the app allows users to enter specific vehicle details, and it returns an estimated resale value in real-time. The application is deployed on Render, making it easily accessible to users.

**Project Objective**

To create an accessible, user-friendly tool that uses machine learning to predict resale values based on various vehicle characteristics.

**Project Structure**

app.py: Main backend file that handles user input, processes it through the machine learning model, and serves predictions to the frontend.
index.html: Frontend HTML file that provides a clean interface for users to enter vehicle details and view the predicted resale value.
Machine Learning Model: A trained predictive model that has been optimized for accurate valuation. The model achieved a Mean Absolute Error (MAE) of 0.82, Mean Squared Error (MSE) of 3.39, and Root Mean Squared Error (RMSE) of 1.84, ensuring reliable performance in valuation estimates.

**Approach**

Frontend: Designed using HTML to provide a user-friendly interface for input and output.
Backend: Flask application that connects the frontend to the machine learning model.
Model Deployment: Deployed on Render for public access, making the application accessible online for ease of use.

**Key Features**

Real-time prediction of resale values based on user-inputted vehicle details.
Simple, intuitive HTML interface.
Deployment on Render for wide accessibility.
Performance Metrics
Mean Absolute Error (MAE): 0.82
Mean Squared Error (MSE): 3.39
Root Mean Squared Error (RMSE): 1.84
These metrics reflect the model's accuracy and the reliability of its predictions.

**Setup**

1. Clone the repository: git clone https://github.com/nakkkul/resale-value-prediction.git
cd resale-value-prediction
2. Install dependencies: pip install -r requirements.txt
3. Run the Flask application: python app.py
4. Access the application at http://localhost:5000 in your browser.
