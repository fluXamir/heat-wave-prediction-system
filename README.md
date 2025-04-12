🌡️ Heat Wave Prediction System
A web-based application built with Streamlit and Plotly to forecast daily temperatures and visualize sky conditions across cities in India. This tool helps highlight temperature trends and is being developed to predict heat waves based on a temperature threshold.

🚀 Features
🔍 User Input
Enter any Indian city (e.g., Mumbai, Patna) and choose the number of forecast days (1–5).

🌡️ Temperature Forecast
Get daily temperature predictions displayed through interactive Plotly charts.

🌤️ Sky Condition Visualization
View sky conditions (clear, cloudy, rainy, etc.) using dynamic visuals for each forecasted day.

🔥 Heat Wave Prediction (Coming Soon)
Automatically detect and highlight potential heat waves when forecasted temperatures exceed a defined threshold (e.g., 35°C).

🚧 This feature is under development.

📈 Interactive Visualizations
Built with Plotly for a visually rich and intuitive experience.

🛠️ Getting Started
✅ Prerequisites
Python 3.7 or higher

pip (Python package manager)

📦 Installation
Clone the Repository
   ```bash
   git clone https://github.com/fluXamir/heat-wave-prediction.git
   cd heat-wave-prediction
   ```
Install manually:
   ```bash
   pip install streamlit plotly
   ```
Run the Application
   ```bash
streamlit run main.py
   ```
The app will open automatically in your default browser. If not, go to:
   ```bash
[streamlit run main.py](http://localhost:8501)
   ```

🧪 How to Use
🏙️ Enter a Location:
Type the name of any city in India.

📅 Select Forecast Days:
Use the slider to choose 1 to 5 forecast days.

🌦️ Choose a View:

Temperature: See temperature trends via Plotly graphs.

Sky Condition: Visual images (sunny, rainy, etc.) based on forecasted weather.

🔥 Heat Wave Prediction:
(Coming Soon) Days exceeding a certain temperature (e.g., 35°C) will be flagged as potential heat waves.

📌 Notes
Forecasting works with both mock/dummy data or real weather data (API integration required).

Heat wave logic is under development.

To use live weather data, integrate a weather API like OpenWeatherMap.

📸 Screenshots
Add screenshots or gifs here to show what the app looks like.

📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.

🤝 Contributions
Got ideas or improvements?
Fork the repo, submit a pull request, or open an issue — contributions are always welcome!

Made with ❤️ by fluXamir
