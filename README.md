# 🌡️ Heat Wave Prediction System

A **web-based application** built using **Streamlit** and **Plotly** that forecasts daily temperatures and visualizes sky conditions for locations in **India**. The system highlights temperature trends and is being developed to include **heat wave prediction** based on a threshold temperature.

---

## 🚀 Features

- 🔍 **User Input**  
  Input any city in India (e.g., *Mumbai*, *Bihar*) and choose the number of forecast days (1–5).

- 🌡️ **Temperature Forecast**  
  View detailed **daily temperature predictions** with interactive graphs.

- 🌤️ **Sky Condition Visualization**  
  View sky conditions as **images** (clear, cloudy, rainy, etc.) for the selected days.

- 🔥 **Heat Wave Prediction** *(Coming Soon)*  
  Automatically detect potential **heat waves** when the forecasted temperature exceeds a threshold (e.g., 35°C).  
  > 🚧 *This feature is under development.*

- 📈 **Interactive Visualizations**  
  Created using **Plotly**, making data analysis engaging and easy to interpret.

---

## 🛠️ How to Run

### ✅ Prerequisites

- Python 3.7+ installed on your system.
- `pip` (Python package installer).

---

### 📦 1. Clone the Repository

```bash
git clone https://github.com/fluXamir/heat-wave-prediction.git
cd heat-wave-prediction
📥 2. Install Dependencies
Using requirements.txt:
bash
Copy
Edit
pip install -r requirements.txt
Or install manually:
bash
Copy
Edit
pip install streamlit plotly
🧾 3. Run the Application
bash
Copy
Edit
streamlit run main.py
The app will automatically open in your browser. If not, navigate to:

arduino
Copy
Edit
http://localhost:8501
🧪 4. Interact with the App
🏙️ Enter Location: Choose any city in India.

📅 Select Forecast Days: Use the slider to pick 1–5 days.

🌦️ Choose View:

Temperature – View temperature trends in a graph.

Sky – View visual representations (images) of sky conditions.

🔥 Heat Wave Prediction:
Feature will soon highlight days with extreme temperatures.

📌 Notes
✅ Forecasting is fully functional using dummy/mock or real weather data.

⚠️ Heat wave prediction logic is not yet implemented.

🌐 You can integrate a weather API (e.g., OpenWeatherMap) for live data.

📸 Images
Here’s what the app looks like:



📄 License
This project is licensed under the MIT License.
See the LICENSE file for more information.

🤝 Contributions
Got ideas or improvements?
Feel free to fork the repo, submit pull requests, or open issues.

Made with ❤️ by fluXamir
