Heat Wave Prediction System
A web-based application built using Streamlit and Plotly that forecasts daily temperatures and predicts potential heat waves for a given location and date range. The app visualizes temperature trends and highlights days where the forecasted temperature exceeds a defined threshold, indicating a heat wave.

Features:
User Input: Input a place in India (e.g., Mumbai, Bihar) and select the number of days to be forecasted from 1-5, select data to view temperature and sky.
Temperature Forecast: Displays daily temperature predictions with a graph and for sky with images.
Heat Wave Prediction: Predicts days when temperatures exceed a set threshold (e.g., 35°C), potentially indicating a heat wave. THIS FEATURE IS YET TO BE IMPLEMENTED.

Visualizations: Interactive Plotly graphs to help users visualize temperature trends.

How to Run:
Prerequisites:
Python 3.7+ installed on your system.
Pip (Python package installer) should be available to install dependencies.

1. Clone the Repository
First, clone the repository to your local machine:
bash
Copy
Edit
git clone https://github.com/yourusername/heat-wave-prediction.git
cd heat-wave-prediction
2. Install Dependencies
Install all required libraries (Streamlit, Plotly, etc.) using pip:
bash
Copy
Edit
pip install -r requirements.txt
If you don't have a requirements.txt file, you can install Streamlit and Plotly manually using:
bash
Copy
Edit
pip install streamlit plotly
3. Run the Application
Once the dependencies are installed, run the application with the following command:
bash
Copy
Edit
streamlit run main.py
This will launch the Streamlit web app in your default browser. If it doesn’t open automatically, you can go to http://localhost:8501 to access the app.
4. Interact with the App
Input Location: Enter a location for the temperature forecast.
Select Number of Days to be Forecasted: Select from the slider the number of days to be forecasted from 1-5.
Select Sky or Temperature: If selected Temperature you can view the graph of the temperature for the selected days and in sky images of the temperature.
Heat Wave Prediction: The app will predict potential heatwaves based on the forecasted temperatures. THIS IS YET TO BE IMPLEMENTED.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Notes:
The prediction system has not been implemented yet, but the forecasting works perfectly fine.

Images:
![image](https://github.com/user-attachments/assets/808d1042-a1d0-4fb2-a2bd-a9a981d6dadd)
![image](https://github.com/user-attachments/assets/11fb1ac4-11af-4bad-a810-c4c8b53ae035)
![image](https://github.com/user-attachments/assets/d622ca9a-5713-403a-b1f9-890bac6c6319)


Contributions:
Feel free to fork the repository, make changes, and create pull requests if you would like to contribute to improving this system. 😊
